# foilmeet
My django site for foilmeet.com


#reminders for me
venv: source ~/eb-virt/bin/activate

run server: 
python3 manage.py runserver


DB stuff make migration


This shell command will export this as a file named requirements.txt:

$ pip freeze > requirements.txt
Once you’ve got your requirements file, you can head over to a different computer or new virtual environment and run the following:

$ pip install -r requirements.txt
That’s assuming you are working in the directory containing requirements.txt. This tells pip to install the specific versions of all the dependencies listed.


Deploy guide:
https://www.youtube.com/watch?v=uiPSnrE6uWE

https://github.com/yeshwanthlm/django-on-ec2 (Remeber to do the pip and Django installs within the manage.py folder)

Running the server: python3 manage.py runserver 0.0.0.0:8000


AWS notes
restarting the serve: sudo systemctl restart foilmeet.service





