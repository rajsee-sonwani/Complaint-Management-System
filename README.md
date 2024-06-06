1. Install and active virtual environment using  <br>
`pip install virtualenv` <br>
`virtualenv env` <br>
`env\Scripts\activate` <br>
2. Change the directory using <br>
` cd Complain_Management_System`<br>
3. Now you need to install python packages to run the app <br>
`pip3 install -r requirements.txt`
4. Migrations <br>
`python manage.py makemigrations`<br>
`python manage.py migrate --run-syncdb`
5. Run Django app <br>
`python manage.py runserver`
