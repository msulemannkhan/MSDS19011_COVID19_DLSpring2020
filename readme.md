# MSDS19011_COVID19_DLSpring2020
This repository contains code and results for COVID-19 classification assignment by Deep Learning Spring 2020 course offered at Information Technology University, Lahore, Pakistan. This assignment is only for learning purposes and is not intended to be used for clinical purposes


# Dataset and Weights
Dataset can be found [here](https://drive.google.com/drive/folders/1-FzZhQO9oHIT9SNOWYoKsuz7fe447vtR?usp=sharing).
Learned weights can be found [here](https://drive.google.com/open?id=1DYWT3tLVw8hNYdasFTEedN-esh3-7ah-).


### Task 1
#### VGG

![vgg_fc_acc](/results/vgg_fc_acc.PNG)
![vgg_fc_loss](/results/vgg_fc_loss.PNG)

Accuracy: 95, 
F1 Score: 0.92


```bash
Test:
[555.,  60.],
[ 22., 863.]
```

#### Resnet

![resnet_fc_acc](/results/resnet_fc_acc.PNG)
![resnet_fc_loss](/results/resnet_fc_loss.PNG)

Accuracy: 85, 
F1 Score: 0.89


```bash
Test:
[535.,  70.],
[ 42., 853.]
```


### Task 2
#### Resnet Last layer

![resnet_last_acc](/results/resnet_last_acc.PNG)
![resnet_last_loss](/results/resnet_last_loss.PNG)

Accuracy: 96, 
F1 Score: 0.93


```bash
Test:
[577.,  37.],
[ 21., 885.]
```


#### Resnet Entire

![resnet_entire_acc](/results/resnet_entire_acc.PNG)
![resnet_entire_loss](/results/resnet_entire_loss.PNG)

Accuracy: 97, 
F1 Score: 0.94


```bash
Test:
[569.,  46.],
[ 17., 868.]
```

#### VGG last layer

![vgg_last_acc](/results/vgg_last_acc.PNG)
![vgg_last_loss](/results/vgg_last_loss.PNG)

Accuracy: 93, 
F1 Score: 0.92


```bash
Test:
[562.,  53.],
[ 26., 859.]
```
