# Text generator which reads in large .txt files, trains a LSTM model on it and outputs text in similar format.

The model uses the following parameter
num_hidden=512,
num_layers=3,
drop_prob=0.5,
use_gpu=True

I tested the model on different datasets. Some models converged quickly, some not at all.

# Counties in Germany
Epochs to trained = 35
Batch_size = 128

### Input
<p align="center">
 <img src="Input.PNG" width="100%" title="Input">
 </p>
 
 ### Output
 <img src="Output.PNG" width="100%" title="Output">



