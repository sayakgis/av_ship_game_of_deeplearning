# Analytics Vidya Ship Images classification

### Public LB score:  0.9757057942, Private LB score: 0.9701055211

Tried with various models:
Resnet, 18, 34, 50, 101, vgg 19, resnext 101_32, seresnext 101 etc.

Used progressive image resizing and data augmentation

Seen improvement of after duplicating class-5 and all classes grey scale images in training

Removed low confidence images from training and retrained

Created multiple submission (5 each day :))

Final submission was with majority voting from all submission where F1 score was more than .95

# Scope of improvement:
Adding focal loss as loss function
