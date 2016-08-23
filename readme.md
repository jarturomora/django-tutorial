Django Quick Start Guide
---------------------------------
## Introduction
This guide describes the required steps to start using Django and Python to create web application using the following specifications:

* Operating system: Ubuntu 16.04 LTS
* Python version 2.7

The steps described in this guide are inspired and based on the [Django Girls Tutorial](http://tutorial.djangogirls.org/) to get started with Python and web development using Django.

## What is Django?

[Via Wikipedia](https://en.wikipedia.org/wiki/Django_%28web_framework%29)

Django (/ˈdʒæŋɡoʊ/ JANG-goh) is a free and open-source web framework, written in Python, which follows the model–view–controller (MVC) architectural pattern. It is maintained by the Django Software Foundation (DSF), an independent organization established as a 501(c)(3) non-profit.

Django's primary goal is to ease the creation of complex, database-driven websites. Django emphasizes reusability and "pluggability" of components, rapid development, and the principle of don't repeat yourself. Python is used throughout, even for settings files and data models. Django also provides an optional administrative create, read, update and delete interface that is generated dynamically through introspection and configured via admin models.

To learn more about Django [visit it's official website](https://www.djangoproject.com/).

## Step 1: Define a working directory
bla

## Step 2: Create a virtual environment

```
# Install the virtualenv module in Python
pip install virtualenv
# Enter to the working directory
cd virtualenv
# Create the virtual environment using this command
virtualenv myenv
``` 

## Step 3: Working with virtualenv
Activate the virtual environment
```
source myvenv/bin/activate
```
> **_(myenv)_** jarturomora@jamsmobile:~/Code/django-tutorial$ 

## Step 4: Install Django
```
# Update pip (optional)
pip install --upgrade pip
# Install Django
pip install django~=1.9.0
```
## Step 5: Create your first Django project
In this tutorial we will create a simple blog.

Start Djando project by running the following command with the virtual environment activated  (this command will create the directory structure of a Django project). The period "**.**" is crucial because it tells the script to install Django in your current directory.
```
django-admin startproject mysite .
```
Now you will have a directory structure like this:
django-tutorial
├───manage.py
└───mysite
        └───settings.py
        urls.py
        wsgi.py
        __init__.py

