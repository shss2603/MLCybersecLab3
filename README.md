# MLCybersecLab3
```
├── data

    └── cl (link to Google Drive)
    
        └── valid.h5 // this is clean validation data used to design the defense
        
        └── test.h5  // this is clean test data used to evaluate the BadNet
        
    └── bd (link to GoogleDrive)
    
        └── bd_valid.h5 // this is sunglasses poisoned validation data
        
        └── bd_test.h5  // this is sunglasses poisoned test data
        
├── Repaired_models

    └── repaired_model_4.h5
    
    └── repaired_model_2.h5
    
    └── repaired_model_10.h5
    
├── bd_net.h5

└── eval.py // this is the evaluation script

```

To evaluate the repaired backdoored model (goodnet G) on a test image (in png or jpeg format), execute 
eval.py by running:

`python3 eval.py <test data directory> <repaired model directory>`

