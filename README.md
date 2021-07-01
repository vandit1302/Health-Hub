# Health-Hub

Health Hub is a ***ML*** and ***NLP*** based project which helps identify the disease given a set of symptoms. The project uses a trusted and authentic [dataset](https://people.dbmi.columbia.edu/~friedma/Projects/DiseaseSymptomKB/index.html), made public by University of Columbia. It uses ML to classify disease based on given symptoms. It uses NLP to first extract symptoms from a text, and later using those extracted symptoms to make prediction of possible disease.

![image](https://user-images.githubusercontent.com/46895613/124161389-fbe82780-daba-11eb-8cc5-98ca57b39087.png)

## 💻 Tech Stack 

* HTML
* CSS
* JavaScript
* Bootstrap
* Flask backend (Python)
* MySQL DB
* Node.js based chat application

## ✨ Salient Features

* Patient Sign-Up / Login
* Doctor Sign-Up / Login
* BMI Calculator
* Disease prediction using Symptom selection
* Disease prediction using Text-based explanation
* Google Maps API to locate nearby hospitals
* Appointment Booking in hospitals
* Chat application
* ML model having 0.99 accuracy
* [Hugging face](https://huggingface.co/) NLP model integration
* MySQL Relational DB integration 
* Open APIs for developers
* Specialist doctor recommendation
* Medicine recommendation


## ⚡ Installation and Usage

The application runs on Flask backend so make sure python and pip are installed in your system.

* Setup a virtual environment
  ```
  pip install virtualenv
  virtualenv venv
  venv\scripts\activate
  ```
* Install all the dependencies
  ```
  pip install -r requirements.txt
  ```
 
* Run the application
  ```
  python main.py
  ```
  
  
## Documentation for Open API 

| Method | URL                                                                | USE                                                     |
| ------ | ------------------------------------------------------------------ | ------------------------------------------------------- |
|  `GET` | http://127.0.0.1:5000/api/details/<b>apitoken</b>                  | Shows your HealthHub Account Details                    |
|  `GET` | http://127.0.0.1:5000/api/login/<b>username~password</b>           | Generates your HealthHub API Token upon successful login|
|  `GET` | http://127.0.0.1:5000/api/symptoms                                 | Generates list of all Symptoms in your Database         |
|  `GET` | http://127.0.0.1:5000/api/diagnosesym/<b>n\~symptom1\~symptom2</b>    | Diagnoses Disease,Medicine and Specialist               |
|  `GET` | http://127.0.0.1:5000/api/diagnosetext/<b>word1 ~ word2 ~ word3</b>    | Diagnoses Disease                                       |
|  `GET` | http://127.0.0.1:5000/api/hospital/<b>apitoken</b>                 | Generates list of Hospitals near you                      |
|  `GET` | http://127.0.0.1:5000/api/register/<b>username ~ password ~ email ~ fullname ~ address ~ bloodgroup ~ age</b>                 | Registers the Patient in the HealthHub Database                      |


## 📷 Screenshots from the implementation

![image](https://user-images.githubusercontent.com/46895613/124163241-04416200-dabd-11eb-8cb5-cb7f2e797288.png)

![image](https://user-images.githubusercontent.com/46895613/124163284-13c0ab00-dabd-11eb-8eda-3bcdaa80b118.png)

![image](https://user-images.githubusercontent.com/46895613/124163301-17ecc880-dabd-11eb-9d37-57263f61b9f3.png)

![image](https://user-images.githubusercontent.com/46895613/124163318-1cb17c80-dabd-11eb-8d04-f1258f8da1e9.png)

![image](https://user-images.githubusercontent.com/46895613/124163333-21763080-dabd-11eb-9f3b-cf317d207f3e.png)

![image](https://user-images.githubusercontent.com/46895613/124163342-263ae480-dabd-11eb-95e9-5828168c916b.png)

![image](https://user-images.githubusercontent.com/46895613/124163363-2b982f00-dabd-11eb-9dd5-3192e912e887.png)

![image](https://user-images.githubusercontent.com/46895613/124163377-305ce300-dabd-11eb-83db-977b908e0927.png)

![image](https://user-images.githubusercontent.com/46895613/124163399-35ba2d80-dabd-11eb-9c88-b7da0e774677.png)

![image](https://user-images.githubusercontent.com/46895613/124163433-39e64b00-dabd-11eb-900a-cd12bdbd5491.png)



## :octocat: Contributors

[Apratim Shukla](https://github.com/apratimshukla6) ,  [Mayank Tolani](https://github.com/mak1082) ,  [Swapnil Mishra](https://github.com/Swapnil0115) ,  [Vandit Sheth](https://github.com/vandit1302) ,  [Raj Sangani](https://github.com/rajlm10) 



