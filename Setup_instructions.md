### Getting Started

1. Clone this repo   
```git clone https://github.com/prajwalgatti/DRL-Collaboration-and-Competition.git```

### Instructions

Follow the instructions in `Tennis.ipynb` to get started with training your own agent!  

2. In the repo is provided a copy on the Tennis for OSX, in case you have a different OS, download the environment from one of the links below:

    - Linux: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Linux.zip)
    - Mac OSX: [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis.app.zip)
    - Windows (32-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86.zip)
    - Windows (64-bit): [click here](https://s3-us-west-1.amazonaws.com/udacity-drlnd/P3/Tennis/Tennis_Windows_x86_64.zip)
    
3. Setup your environment

   ```
   conda create --name continuous_control python=3.6
   source activate continuous_control
   conda install -c pytorch jupyter
   pip install unityagents
   ```
   
4. Run
   (From project folder)
   ```
   source activate continuous_control
   jupyter notebooks
   ```

5. Open and Run:   
   ```Tennis.ipynb```
