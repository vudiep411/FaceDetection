# Object Detection Architechture
Template to build a face detection model with tensorflow and python

# Installation
1. Follow the notebook step 1 to install all dependencies needed.
2. Create folder structure like below
    ```bash
    ├───.ipynb_checkpoints
    ├───aug_data
    │   ├───test
    │   │   ├───images
    │   │   └───labels
    │   ├───train
    │   │   ├───images
    │   │   └───labels
    │   └───val
    │       ├───images
    │       └───labels
    └───data
        ├───images
        ├───labels
        ├───test
        │   ├───images
        │   └───labels
        ├───train
        │   ├───images
        │   └───labels
        └───val
            ├───images
            └───labels
    ```
3. Now create your own data and labels and put them inside **/data/\***