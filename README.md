# FORTH-TRACE Dataset version 1.0

Katerina Karagiannaki (1,2)  
Athanasia Panousopoulou (1)  
Panagiotis Tsakalides (1,2)  

(1) - Signal Processing Laboratory (SPL), ICS - FORTH  
(2) - Computer Science Department, University of Crete 


## EXPERIMENTAL SETUP

The dataset is collected from 15 participants wearing 5 Shimmer sensor nodes 
on the locations listed in Table 1. The participants performed a series of 16 
activities (7 basic and 9 postural transitions), listed in Table 2.

The captured signals are the following: 

* 3-axis accelerometer 
* 3-axis gyroscope 
* 3-axis magnetometer 

The sampling rate of the devices is set to 51.2 Hz.


## DATASET FILES

The dataset contains the following files:

* partX/partXdev1.csv 
* partX/partXdev2.csv 
* partX/partXdev3.csv 
* partX/partXdev4.csv 
* partX/partXdev5.csv 

Where X corresponds to the participant ID, 
and numbers 1-5 to the device IDs indicated in Table 1.

Each .csv file has the following format:

* Column1: Device ID 
* Column2: accelerometer x 
* Column3: accelerometer y 
* Column4: accelerometer z 
* Column5: gyroscope x 
* Column6: gyroscope y 
* Column7: gyroscope z 
* Column8: magnetometer x 
* Column9: magnetometer y 
* Column10: magnetometer z 
* Column11: Timestamp 
* Column12: Activity Label 


## Table 1: LOCATIONS

1. Left Wrist
2. Right Wrist
3. Torso
4. Right Thigh
5. Left Ankle


## Table 2: ACTIVITY LABELS
(Arrows (->) indicate transitions between activities)

1. stand 
2. sit 
3. sit and talk 
4. walk 
5. walk and talk 
6. climb stairs (up/down) 
7. climb stairs (up/down) and talk 
8. stand -> sit 
9. sit -> stand 
10. stand -> sit and talk 
11. sit and talk -> stand 
12. stand -> walk 
13. walk -> stand 
14. stand -> climb stairs (up/down), stand -> climb stairs (up/down) and talk 
15. climb stairs (up/down) -> walk 
16. climb stairs (up/down) and talk -> walk and talk 

## License:
Use of this dataset in publications must be acknowledged by referencing the following publications:

* Katerina Karagiannaki, Athanasia Panousopoulou, Panagiotis Tsakalides. A Benchmark Study on Feature Selection for Human Activity Recognition. ACM International Joint Conference on Pervasive and Ubiquitous Computing (UbiComp), ACM, 2016.
