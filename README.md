Face Recognition Project

Step 1:- 
    import sqlite3  -> Module for create database
    import webbrowser -> Used into open a browser (By default google chrome open)

Step 2: - 
    install opencv -> pip install opencv-python
    install Numpy -> pip install numpy
    
Step 3: 
     Then haar_cascade classifier is used to create train data to train the model . After traing we have tested the model .
     Capture a video & take 20 samples (images) of it .
     Use LBPH model to recognise face . PBPH model used into recognise side & front face  .
     take the username form user (First time at the time of train the model )
     When second time user will come it will identify & if efficiency is greate than 90% it will open a browser for us .(In our case google will open .)
    
