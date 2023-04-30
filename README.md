# MS_Project

Face-Attendence is a face-recognition participation framework that schedules events using Google Calendar. EJS is used as the templating language, and Javascript is used 
to run it on node.js. The program's backend stores user information in MySQL. Face-api.js, a Javascript module performing convolutional brain organisations, is used by 
the face recognition component of the programme to recognise and distinguish faces and to provide face tourism attractions. On top of the tensorflow/tfjs-center API of 
tensorflow.js, face-api.js is a javascript API. FaceID uses the Google Calendar API to retrieve events from a user's Google Calendar and concentrate the date, time, and 
name of the events that users have added to their schedule.


# Instruction

1 . git clone https://github.com/shri-pandey/MS_Project.git \
2 . cd ./Face-Attendence \
3 . connect to mysql using XAMPP \
4 . open phpmyadmin and put your credential in db/connect.js \
5 . create a new table named "faceid" \
6 . click on SQL in phpmyadmin \
7 . copy code from faceid.sql and paste in SQL tab ,present is phpmyadmin \
8 . go to terminal run "npm i" \
9 . then ,"npm run dev" \
