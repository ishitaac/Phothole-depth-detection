<h2>Pothole Depth Detection</h2>

<h3>Hackathon: WIEHack 4.0</h3>

<h3>Team Number: 23</h3>
<h3>Team Name: ML Wizards</h3>
<h3>Team Members: Ishita Choudhary, Deepakshi Mahajan, Shraddha Sharma</h3>
<hr>

<h3>Project Description: </h3>
<p>The number of potholes in the world has rapidly increased due to the growth of vehicles, temperature changes, and the concentration of the population. Potholes cause danger in driving and reduce passengers' comfort. Therefore, an accurate prediction of number of potholes provides timely maintenance and rehabilitation, and also it enhances safety for drivers. Various machine learning methods were then employed to develop an optimal model that provides the highest accuracy in predicting pothole occurrence. The project also suggests a computer vision-based system for spotting potholes based on the image segmentation method. </p>
<hr>

<h3>Proposed Solution:</h3>
<p>The developing nations like India use manual inspection methods to recognize the potholes leading to inaccurate estimation as it is highly dependent on individual experience. These manual inspection methods require human interventions that are time consuming and costly. </p>

<p>Therefore, we propose a vehicle-based computer vision approach to identify and analysis potholes, vehicles using a car-mounted/ street-mounted camera. The results will then be logged together with the GPS coordinates of the pothole for use by technical experts and road maintenance agencies and to aid drivers. Drivers will immediately get a warning notification to take immediate action if potholes are detected in real-time. 
Our model will also calculate the depth of the pothole and send an alert to the local PWD office for the immediate repair of the road.</p>
<hr>

<h3> Our approach for Pothole detection</h3>
<p>We employed YOLOv7. We started with the YOLOv5. The outcome was encouraging, but further accuracy was anticipated. The given CSV file (from Kaggle) was initially converted to the YOLO format. Despite the application of image processing, the accuracy did not improve. Thus, we utilized the provided images without any preprocessing. Image augmentation was carried out using the albumentations library, which significantly boosted the score. src folder contains all the helper scripts.</p>
<hr>
