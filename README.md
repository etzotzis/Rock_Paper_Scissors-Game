This is a Machine Learning Project about Image Recognition

Project's instructions: 

    https://drive.google.com/file/d/19sBaIygmYRiXQgSNqLsjTgdDHiFnAEZP/view

Dataset:

    https://www.kaggle.com/datasets/drgfreeman/rockpaperscissors

github link: 

    https://github.com/etzotzis/Rock_Paper_Scissors_Game

Files:

    Rock_Paper_Scissors_CNN.ipynb
    
    Rock_Paper_Scissors_RF.ipynb

Results:

    Both files are self working and implement the Project's requirements using either CNN (Rock_Paper_Scissors_CNN.ipynb) or Random Forests (Rock_Paper_Scissors_RF.ipynb).
    
    The user can change the following in both code files:
        x_pixels = 60 # Number of X pixels - Ratio ideally, should be 3/2 (with Y pixels)
        y_pixels = 40 # Number of Y pixels
        N = 1000  # Number of turns
        p1 = 0.5  # Probability of applying vertical flip
        p2 = 0.5  # Probability of applying horizontal flip
        sigma = 0.05  # Standard deviation for adding noise

    Both ways can achieve a very good accuracy predicting the image's class (Rock Paper or Scissors) in the first place. 
    However, RF cannot cope with the opponent agent's flips and noise addition and its accuracy falls near random choice. On the other hand, CNN keeps a very good accuracy even after the image "corruption".

    
Author:

    Tzotzis Evangelos

