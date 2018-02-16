# Image_Classification_Using_Tensorflow

Download the pre-trained model here:http://download.tensorflow.org/models/image/imagenet/inception-2015-12-05.tgz
Extract in local setup.


Run the retrain.py with required arguments to train the model.

EX:
 
  python retrain.py --image_dir=path/to/train/images --output_graph=/path/to/save/outputmodel --output_labels=path/to/output/lables
  --model_dir=path/to/downloaded/folder
 

edit the code in predict.py put your trained outputmodel.pb, your_lables.txt, your_testing_img.jpg 

run predict.py

python predict.py

