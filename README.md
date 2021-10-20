# Mouse_Disease_Detector
# Mouse disease identification for an image Uploaded to an Interactive Website created using Flask

## Plan:
1. Use bing image downloader to collect images
2. Collect images for 10 diseases
3. Label Images
4. Train Classifier
5. Create Mobile App using Tensorflow Lite
6. Deploy

## Research Papers:
1. https://onlinelibrary.wiley.com/doi/abs/10.1002/rob.21921

## Dataset Creation:

### Phase 1:
- 3 Diseases :- Emaciation, Dermatitis, Blepharitis 
- Images collected from https://www.criver.com/resources/info-pi-rm-common-rodent-health-conditions-poster
- Label tool :- https://github.com/tzutalin/labelImg
- Tutorials :- https://www.youtube.com/playlist?list=PLeo1K3hjS3ut49PskOfLnE6WUoOp_2lsD

### Phase 2:
- Train Classifier 
- Choose latest augmentation library AugLy from Facebook
- Latest Model

### Phase 3:
- Create a Web app using Flask to deploy the model
- https://medium.com/swlh/how-to-create-an-interactive-machine-learning-web-application-using-flask-and-heroku-5ae76a45bfc5
