# AlphaNumeric-Detection-DL
Playing around with DL, basic models </br>
In each task directory, the python notebook with the task name has the model source code. The trained models are uploaded for both tasks and, can be used using load_model method.

## Task 1
In the first task, a model is created which attempts to distinguish Alphabet from numeric values. A simple binary classifier using CNN is built. </br>
There is a 80-20 percent split between alpha-numeric values in the data. Therefore, an attempt to rectify the classification imabalnce has been made using initial bias and class weights. The tensorflow documentation was used as reference and is linked in the notebook.
The model reports an accuracy of 93%. 
## Task 2
The second model classifies the 47 alpha-numeric values considered. A simple CNN is used for this. The class-wise model report is included in the notebook. </br>
The model can be used using the prediction notebook. The assumption is that the input is a column-major image vector.
