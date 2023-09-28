# Sportsera

This web application enables the user to book a sporting venue of their choice, which are recommended based on the safety guidelines published by the Government. This application also provides a feature of monitoring the correctness while performing an exercise routine at home itself.
## Installation & Setup

### NodeJs: 
Use the [npm](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm) registry to install all the required NodeJs libraries to run this project.

```bash
npm install
```

### Python:
To install python to the system, refer this link - [Python](https://www.python.org/downloads/)

To install anaconda to the system, refer this link - [Anaconda](https://docs.anaconda.com/anaconda/install/)

Open Anaconda Prompt and type the command (to make a new virtual environment). 

```bash
conda create -n ENVNAME
```

To activate the new virtual environment.

```bash
conda activate ENVNAME
```
Now one should download the necessary libraries (in this virtual environment) as follows:

#### Opencv
```bash
conda install opencv
```

#### SQLite3
```bash
conda install -c blaze sqlite3
```

#### face-recognition
Since, the project has been executed in Windows, the following link would be helpful to provide guidance on installing 'face_recognition' library in Windows systems - [Youtube video](https://youtu.be/xaDJ5xnc8dc)

### SQLite database browser:
The following link is from where remote SQLite database browser can be downloaded - [SQLite](https://sqlitebrowser.org/dl/)

Data of different grounds must be filled into the GROUNDS table of the database and the time slots should be mentioned in the TIMESLOTS table. An example of this data is as follows -

![Alt Text](/public/images/Capture1.JPG)

![Alt Text](/public/images/Capture2.JPG)

### Speech interface:
Install "Handsfree for web" google chrome extension, which would be present in the chrome extension store.


## Usage
To run the project, open Anaconda prompt (and activate the virtual env in which all the python dependencies are installed) and go to the root directory of the project (within the conda virtual environment setup for the project), and type
```bash
nodemon server.js
```
The application takes atleast 3 min to start. Along with that, open the 'Handsfree for Web" extension, which is installed in the Chrome browser.
Once the message in the console prints "App started on port 3000", in the URL section of the browser, type [http://localhost:3000/](http://localhost:3000/)


## Output
![image](https://user-images.githubusercontent.com/51831161/156632097-8c5fde36-5e4f-4554-9c3c-390215468ea4.png)

Home Page

![image](https://user-images.githubusercontent.com/51831161/156632432-a8e0f366-6240-4d3f-9fa9-408f7d114a87.png)

Sign Up Page

![image](https://user-images.githubusercontent.com/51831161/156632611-2185f377-d8de-4c52-8e59-3c267130b88f.png)

Login Page

![image](https://user-images.githubusercontent.com/51831161/156632769-d3d1f2f2-052e-418c-b6a5-58000a780d7e.png)

Landing Page

![image](https://user-images.githubusercontent.com/51831161/156632878-8e051f82-ee52-4ba7-a171-8b2795da4b81.png)

Venues to book (Recommendations)

![image](https://user-images.githubusercontent.com/51831161/156632998-e4eb75d0-75bc-43ba-8217-d25bfd98ec57.png)

Select Date

![image](https://user-images.githubusercontent.com/51831161/156633109-b9f67f18-27a0-4341-8ad4-1ebdafd63cbd.png)

Home Workout Pose Correction
