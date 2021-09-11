## Personal Blog
This is a minimalistic blog built with Django. I have hosted it on Python Anywhere. You can check it out [here](https://vishnusreddy.pythonanywhere.com/).  

## Features
1. Multiple Author
2. Supports a WYSIWYG Editor
3. Reader Comments

## Setup and Running
First clone the code from the respository using the below commands. 
```
git clone https://github.com/vishnureddys/blog.git
```
Next, create a virtual environment using the code below. 
```
python -m venv env
./env/scripts/activate
```
Now, install the requirements. 
```
pip install -r requirements.txt
```
Then, make the migrations, create super user and run the server. 
```
python manage.py makemigrations
python manage.py migrate
python manage.py createsuperuser
python manage.py runserver
```
To add content, you can proceed to the admin page at [http://127.0.0.1:8000/admin](http://127.0.0.1:8000/admin).

## Contributing
Feel free to raise a pull request if you want to improve the project. Some suggested improvements are:
1. Allow guest posting i.e. user registration. 
2. Syntax highlighting in content. 

## License
This is opensourced under the MIT License