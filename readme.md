# Characters Classification using Deep Learning Computer Vision
## Colab
### Prepare
1. parepare a google account
2. log in your google account
3. download your personal kaggle.json
4. link to https://colab.research.google.com/?utm_source=scs-index to create first colab jupyter notebook
5. set up your google drive location
6. upload lab2_final_MobileNetV3Large.ipynb to your googld drive

### Run
1. go to your googld drive
2. open lab2_final_MobileNetV3Large.ipynb
3. Edit -> Notebook Settings
4. select GPU from the Hardware Accelerator drop-down
5. cell -> run all
6. ask link your google drive -> select your account
7. get model and test.csv

## Local
### Prepare
1. prepare gpu, anaconda
2. download anaconda
3. create conda environment in Python 3.6.13
4. pip install -r requirements.txt
6. install cuda(https://www.uj5u.com/qita/289434.html)
5. install the correspond pytorch version with your cuda(https://pytorch.org/get-started/previous-versions/) 

### Run
1. put the dataset in './datasets/'
2. open jupyter notebook
3. open lab2_final_MobileNetV3Large.ipynb
4. cell -> run all
5. get model and test.csv

# Model
## Large
![image](https://github.com/tang03130313/Characters-Classification-using-Deep-Learning-Computer-Vision-MobileNet/blob/main/image/result_Mobilenetv3Large.png)

## Small
![image](https://github.com/tang03130313/Characters-Classification-using-Deep-Learning-Computer-Vision-MobileNet/blob/main/image/result_Mobilenetv3Small.png)

# Score
![image](https://github.com/tang03130313/Characters-Classification-using-Deep-Learning-Computer-Vision-MobileNet/blob/main/image/score-1.png)
![image](https://github.com/tang03130313/Characters-Classification-using-Deep-Learning-Computer-Vision-MobileNet/blob/main/image/score-2.png)