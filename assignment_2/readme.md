TASK 2.3.1

(1) First, necessary libraries like numpy and sklearn are
imported.
(2)Then the train and test files are loaded.
(3)Then “np.vstack and np.hstack” are used .np.vstack and
np.hstack are NumPy functions for vertically stacking
arrays and horizontally stacking arrays, respectively.
np.vstack takes a sequence of arrays and stacks them
vertically to form a new array. The arrays must have the
same number of columns, otherwise a ValueError will be
raised. For example, if we have two arrays a and b, both
with shape (3, 2), we can vertically stack them using
np.vstack((a, b)).
(4) np.hstack takes a sequence of arrays and stacks them
horizontally to form a new array. The arrays must have the
same number of rows, otherwise a ValueError will be
raised. For example, if we have two arrays a and b, both
with shape (3, 2), we can horizontally stack them using
np.hstack((a, b)).
(5) Train set is divided into 20 equal parts randomly.
    Then 21 datasets are created(20 train sets and 1 test set).
    20 train sets and test set are then printed to the console.