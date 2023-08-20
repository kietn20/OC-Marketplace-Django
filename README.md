# [OC-Marketplace](https://oc-marketplace-django.onrender.com)

Community-driven marketplace for buying/selling items for Orange County.

## Description

A Django web application that allow users to sign-up/log-in for the purpose of selling, buying, or communicating with the local Orange County communities. 

## Getting Started

### Dependencies

from requirements.txt
* Django
* django-environ
* django-storages
* asgiref
* boto3
* botocore
* dj-database-url
* gunicorn
* jmespath
* Pillow
* psycopg2-binary
* python-dateutil
* s3transfer
* six
* sqlparse
* typing_extensions
* tzdata
* urllib3

### Installing

* Download repository

### Executing program

* Activate a virtual environment 
* Make a cloud Postgresql Database
* Establish a connection with AWS S3
* Configure .env with the missing requirements
* Make migrations and migrate
```
env/scripts/activate (for windows)
python manage.py makemigration
python manage.py migrate
python manage.py runserver
```

## Help

Remember to turn DEBUG to True to fix bugs

## Authors

Kiet Nguyen: 
* [LinkedIn](https://www.linkedin.com/in/kiet-nguyen-232458276/) 
* GMAIL: kietnguyen3698@gmail.com

## Version History
* 0.1
    * Initial Release

## License

This project is licensed under the MIT License - see the LICENSE.md file for details

## Acknowledgments

Inspiration
* Facebook's Marketplace
