Browse through the command prompt window to the desired location through the ‏"cd" command. 
Create a virtual environment by using the command - "py -m venv <environment name>".
Activate the virtual environment by using "<environment name>\Scripts\Activate". After activation the virtual environment we created is shown before the location.
Install django by the command "pip install django" if it is not installed.
Using cd command go to task_001 folder using "cd task_001.
then command "pip install django-crispy-forms".
After the installation gets complete run the server by the command "py manage.py runserver".
After the server is running we could see the server link "http://127.0.0.1:8000/". Control click this link that will gets to our login page of the webpage.
After giving username which is set it as the email id and password we are directed the home page where the user can view and delete the user.
The credentials to enter is "Email -nsm@gmail.com and password =12345".If you put the invalid credentials an error message will pop up.
There is a create icon in which the user can add new people.
The logic can be seen in the following folder "task-001>Usermanage>views.py" by opening it in visual studio code software which i normally use.
