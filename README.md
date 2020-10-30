# Log 0.1
1. Downloaded dataset from https://github.com/garythung/trashnet
2. Diveded data into approximately train (50%) validate(25%) and test (25%) folders
3. Loaded data using flow_from_directory like in cats_and_dogs_example but with class_mode = "categorical"
4. Built network similar to the one from cats_and_dogs_example, but with less nodes, 6 output nodes and loss='categorical_crossentropy'.
5. Trained the model and plotted data similar to cats_and_dogs example
6. Overtraining after ~5 epochs, ended at around 55% accuracy
