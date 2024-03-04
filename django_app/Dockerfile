FROM python:3.10.13
LABEL maintenair="ndamagaye" email="ndamagaye64@gmail.com"
#Set the working directory
WORKDIR /app
#Copy the Django project files into the image
COPY . .
#Install Django and other required packages
RUN pip install -r requirements.txt
EXPOSE 8000
#Start the Django development server
CMD ["python", "manage.py","runserver", "0.0.0.0:8000"]

