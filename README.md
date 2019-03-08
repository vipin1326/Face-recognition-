# Face-recognition-

Object Detection using Haar feature-based cascade classifiers is an effective object detection method proposed by Paul Viola and Michael Jones in their paper, "Rapid Object Detection using a Boosted Cascade of Simple Features" in 2001. It is a machine learning based approach where a cascade function is trained from a lot of positive and negative images. 
It is then used to detect objects in other images.We can draw the bounding boxes over the area of face in the image and we have to perform the recognition on that part of image.
 
![image](https://user-images.githubusercontent.com/44171241/54035794-22923e00-41e0-11e9-82ad-2bbfd962a4d3.png)


And then we train LBPH face recognizer which is present in opencv2 using the images we have in our dataset.
And we save the model as trainner.yml and labels as labels.pickle file. 

Now we head on to face.py notebook and we can use do live streaming using opencv2 and we the perform the face recognition on the live video we have using the model we have which we already saved as trainner.yml


![image](https://user-images.githubusercontent.com/44171241/54035571-b0215e00-41df-11e9-9d3e-0023a2e22602.png)
