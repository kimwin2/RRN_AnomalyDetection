# RRN (Reconstructive Recurrent Network)

## RRN architecture
![Screenshot from 2020-10-27 19-12-51](https://user-images.githubusercontent.com/43340417/97287884-760b4100-1888-11eb-8d1d-f5c2e2388b11.jpg)

## Usage
* Clone this repo:
```git clone https://github.com/kimwin2/RRN_AnomalyDetection.git```
* Download datase:
``` 
python3 0_download_dataset.py
```
* For training: 
```
python3 1_train.py
```
* For testing: 
```
python3 2_anomaly.py
```
* Display result:
```
python3 3_display_result.py
```


## network and etc files
* preprocess_data.py : This code is for preprocessing dataset.
* model/model.py: This code is for the lstm based encoder-decoder architecture.

## paper

Y.-H. Yoo, U.-H. Kim and J.-H. Kim, "Recurrent Reconstructive Network for Sequential Anomaly Detection," IEEE Transactions on Cybernetics, Accepted, DOI: 10.1109/TCYB.2019.2933548, Jul. 2019.

