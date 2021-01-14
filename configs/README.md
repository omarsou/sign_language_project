This folder contains various config files needed to run experiment.
- **sign.yaml** => Base configuration (the paper's one)

- **sign_body2d.yaml** => Configuration for running experiment with body2d keypoints

- **sign_body3d.yaml** => Configuration for running experiment with body3d keypoints

- **sign_hand2d.yaml** => Configuration for running experiment with hand2d keypoints

- **sign_hand3d.yaml** => Configuration for running experiment with hand3d keypoints

- **sign_face2d.yaml** => Configuration for running experiment with face2d keypoints

- **sign_face3d.yaml** => Configuration for running experiment with face3d keypoints

- **sign_bodyface3d.yaml** => Configuration for running experiment with body3d + face3d keypoints

- **sign_hand2dbody2d.yaml** => Configuration for running experiment with hand2d + body2d keypoints

- **sign_hand2dbody3d.yaml** => Configuration for running experiment with hand2d + body3d keypoints

- **sign_hand2dbody3dbody2d.yaml** => Configuration for running experiment with hand2d + body3d + body2d keypoints

- **sign_hand3dbody2d.yaml** => Configuration for running experiment with hand3d + body2d keypoints

- **sign_hand3dface2d.yaml** => Configuration for running experiment with hand3d + face2d keypoints

- **sign_hand3dface2dbody2d.yaml** => Configuration for running experiment with hand3d + face2d + body2d keypoints

- **sign_cnn_avg** =>  Configuration for running experiment with adding Dope hidden features as hidden states to the encoder (early)

- **sign_features_avg** => Configuration for running experiment with concatening DOPE hidden features and Sign features (early)

- **sign_latefusion_avg** => Configuration for running experiment with adding DOPE hidden features after the encoder (addition / late fusion)

- **sign_paragraph** => Configuration for running experiment with inputting paragraph instead of sentence

We can either modify the config file by opening the file with text editor for instance or we can open it on a notebook and modify it.
Sometimes I used the notebook config_modify.ipynb to modify the config files.
