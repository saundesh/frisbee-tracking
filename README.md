# Detection and Tracking in Ultimate Frisbee

For this project, I implemented detection and tracking in the sport of ultimate frisbee using OpenCV. Code for v1 can be found in the 'project-v1.ipynb' file. The output video of my result can be found as 'final-result.mpeg' or at https://youtu.be/-Bu1vcGuILg

To run the code:
1. Move clip-5.mp4 into a new directory ./data/input/
2. Place clip-5.txt into a new directory ./homography/
3. Create directories for the following:
    - ./images/input/clip-5/
    - ./images/output/clip-5/aligned/
    - ./images/output/clip-5/background/
    - ./images/output/clip-5/foreground/
    - ./images/output/clip-5/track/
    - ./images/output/clip-5/minimap/
    - ./mean/
    - ./median/
4. Open 'project-v1.ipynb' in a Jupyter notebook and make sure clip_num = 5
6. Click on 'Kernal > Restart & Run All' in the menu
6. Code will use 'clip-5.txt' as homographies so it won't take too long to run
7. Once everything runs, replica of output video can be found in main directory

Currently, I am working on v2 which will be more robust and have new features!