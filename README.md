# Cancer Detection Web App

## Available at https://lung-cancer-detection-method1.herokuapp.com/

## Details

The following were used for model **training** (see [requirements.txt](requirements.txt)):    
- fastai:  version 1.0.52
- PyTorch:  version  1.0.0
- Python:  version 3.6

A SqueezeNet pretrained on the ImageNet dataset was used to train the classifier.

The following were used for model **deployment**:    
- Heroku (Free Dyno)
- Flask:  version 1.0.2
- gunicorn
