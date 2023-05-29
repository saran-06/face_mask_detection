# face_mask_detection

	Hello guys, I have completed one AI project while learning deep learning concepts. I have completed facemask detection using deep learning techniques. Facemask detection is an essential thing when it comes to pandemic situations.
	I have used a Convolution neural network. But in the model instead of using convolution layers, I have used Mobilenet-v2.
	Steps
		1)install required 	libraries(TensorFlow,Keras,imutils,numpy,opencv,scipy)
		2)data preprocessing(resize all images,convert 	images into array to feed this to neural network)
		3)data splitting(split the dataset into training and 	testing set)
		4)model(base model(mobile-net model),head model)
		5)data training(epoch-20,learning_rate=	1e-4,batch_sizze=32)
		6)created face detection and video streaming to show 	the results in the frame using OpenCV.
with_mask=green color,without_mask=red color


![plot](https://github.com/saran-06/face_mask_detection/assets/109670288/9a5347e8-f8cd-446a-90ac-cb1c71d6f357)

In this plot the model performance is visualized using matplotlib

