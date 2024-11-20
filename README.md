# Vehicle-Counter-using-OpenCV
Vehicle detection and counting are very important in traffic monitoring, toll collection, military applications, etc. The technology of vehicle detection in the captured video has an implementation in a variety of fields. In this project, we implemented a basic model of Vehicle detection and counting. The video clip is taken as input, many frames are extracted and the background is estimated along with shadows.Several algorithms are used for subtracting the background on input video materials. The data obtained during the analysis of the algorithms are compared The most efficient algorithms that coped with the task most quickly, accurately, and with the least expenditure of resources, were identified, as well as those that coped with the task the worst.

## Features
- Vehicle detection in real-time from video input
- Vehicle counting
- Background subtraction with shadow removal
- Comparison of different background subtraction algorithms based on accuracy, speed, and resource usage
- Easy-to-extend framework for further improvements

## Algorithms Used
Several algorithms for background subtraction are tested and compared:
- **MOG2 (Mixture of Gaussians)**: Efficient and accurate background subtraction method.
- **KNN (K-Nearest Neighbors)**: Another background subtraction algorithm, useful in certain scenarios.
- **BackgroundSubtractorGMG**: A probabilistic foreground/background segmentation algorithm.
  
The results are compared based on:
- Speed of execution
- Accuracy of vehicle detection
- Resource usage (CPU/memory)

## Dependencies
Make sure you have the following installed:
- Python 3.x
- OpenCV
- NumPy
