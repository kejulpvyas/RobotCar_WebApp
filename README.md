# RobotCar_WebApp

Here are the steps required to receive live streaming video from the camera mounted on the robot car and route it in the web application:

•	Step 1: Run the client web application on the local host as per the instructions below. 

•	Step 2: Enter the IP address of the raspberry pi server which controls the robot car. 

•	Step 3: Once IP address is known to the client web application; it will initiate an SSH connection with the raspberry pi server. 

•	Step 4: After the SSH connection is successful, the client web application invokes initialization function sudo.start which is executed on the raspberry pi server which in turns trigger live streaming function. 

•	Step 5: After successful invocation of sudo.start, application redirects live streaming from the camera mounted on the robot car to the client web application.
