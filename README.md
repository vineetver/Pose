## About

Human pose estimation is the task of detecting human figures in images and videos and estimating their pose.

The dataset is of human poses while exercising in the gym. The activities are named in the first column. The dataset is the result of feeding exercise videos into Google's [Blazepose](https://ai.googleblog.com/2020/08/on-device-real-time-body-posetracking.html) pose estimation model. The model detects human figures in the video and estimates their pose. The first row of the dataset is the name of the activity and the remaining rows are the estimated coordinates of the joints detected by the model.

I created a gif of the human pose estimation results. The gif shows the different activities detected in the video and the estimated pose of the human figure in each frame. The spine angle is one of the most important things to track when exercising. The gif below shows the estimated spine angle for each frame.

![Gif](https://github.com/vineetver/Pose/blob/main/bench%20jump.gif)

I also implemented PCA with three different clustering algorithms to distinguish different movements/group similar excercises together.

## Getting Started

### Dependancies

List of all the libraries you need to run the code.

  ```sh
  Python 3.x
  Numpy
  Pandas
  Matplotlib
  Scikit-learn
  scipy
  ```


<!-- USAGE EXAMPLES -->
## Usage

  ```sh
  $ conda create -n "env-name" python=3.x, anaconda
 
  $ conda activate "env-name"
  
  $ cd Pose
  
  $ jupyter notebook
  ```

## Roadmap

- [x] Create the gif
- [x] Normalize the data for PCA
- [x] Apply PCA
- [x] Kmeans
- [ ] Softclustering
- [ ] Birch
- [ ] Evaluation


## License

Distributed under the MIT License. See `LICENSE.md` for more information.


## Contact

Vineet Verma - vineetver@hotmail.com - [Goodbyeweekend.io](https://www.goodbyeweekend.io/)
