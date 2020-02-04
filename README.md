# Modified-SqueezeNet
Comp 551-mini4 
Reproducing Squeeznet and making some modifications

Pytorch implementation of Squeezenet model as described in https://github.com/gsp-27/pytorch_Squeezenet

Pytorch implementation of AlexNet model as described in https://github.com/bearpaw/pytorch-classification

For each folder, the definition of Squeezenet model is present model.py. The training procedure is in the file main.py The pretrained model weights are included in each folder as well.

Command to train the Squeezenet model on CIFAR 10 data is:

python main.py --batch-size 16 --epoch 20 Feel free to use your desired batch-size and number of epochs. Other options which can be used are specified in main.py

Eg: if you want to use a pretrained_model python main.py --batch-size 32 --epoch 10 --model_name "pretrained model"

Eg: want to check number of parameters, etc. python main.py --batch-size 32 --epoch 10 --want_to_test True

NB: The learning rate is set at 1e-3
