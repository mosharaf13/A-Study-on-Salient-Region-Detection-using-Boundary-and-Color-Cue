# Visual saliency detection using boundary and color cue


### Usage

The branch `main` points to single image saliency detection algorithm. To run the algorithm do as follows

#### Prerequisites
    Opencv
    GCC

#### On linux debian based systems
    cd opencvtest
    g++ -g -std=c++11 Source.cpp -o  output $(pkg-config --cflags --libs opencv)
    sudo chmod +x output 
    ./output

The output will generate four images denoting 4 saliency map listed below. 

1. Global saliency map
2. Color saliency map
3. Boundary saliency map
4. Final saliency map

Below diagram denotes relationship between these maps


## Results

<p align="center">
  <img alt= "Initial image" src="https://github.com/mosharaf13/A-Study-on-Salient-Region-Detection-using-Boundary-and-Color-Cue/blob/main/opencvtest/24071.jpg">
</p>


<p align="center">
  <img alt= "Boundary map" src="https://github.com/mosharaf13/A-Study-on-Salient-Region-Detection-using-Boundary-and-Color-Cue/blob/main/opencvtest/Boundary%20saliency%20Map.jpg">
  <img alt= "Color map" src="https://github.com/mosharaf13/A-Study-on-Salient-Region-Detection-using-Boundary-and-Color-Cue/blob/main/opencvtest/COLOR%20SALIENCY.jpg">
  <img alt= "Global map" src="https://github.com/mosharaf13/A-Study-on-Salient-Region-Detection-using-Boundary-and-Color-Cue/blob/main/opencvtest/global%20saliency%20Map.jpg">
</p>


<p align="center">
  <img alt= "Final saliency map" src="https://github.com/mosharaf13/A-Study-on-Salient-Region-Detection-using-Boundary-and-Color-Cue/blob/main/opencvtest/Final%20saliency%20Map%20With%20Smoothing.jpg">
</p>
