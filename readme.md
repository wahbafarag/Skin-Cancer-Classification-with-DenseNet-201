# Flask Skin Cancer Classification App (93% accuracy)


### How to use 

* In order for this app to work with you :
    - Create static folder where we would save uploaded images 
    - templates folder where u have all ur templates 
    - app.py : flask app 
    - Open Dense_Net_201 and run the whole notebook then save ur model
    - Your model should be in the same dir with other folders


### What this app Provide
* there are 4 templates : 
    - home : more info about who we are, what is skin cancer and how to protect yourself
    - types : more info about the 7 Type we classify ( actinic keratosis,melanoma,basal cell carcinoma,pigmented benign keratosis,squamous cell carcinoma,vascular lesion,nevus)
    - index and predict : here you can upload an image to classify 
        - we provide its type , Benign or Malignant and show the image you uploaded
    - history : you can view your prodiction history 