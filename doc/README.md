### How to run backend?
#### ::Without using Docker::
>
*Step:1 Clone project from github*

>Using HTTP
`git clone https://github.com/mn-48/Django-4.2-GraphQL-Template.git`

>Using SSH
`git clone git@github.com:mn-48/Django-4.2-GraphQL-Template.git`

*Step:2 Go to backend directory where exist manage.py*
`cd backend`


*Step:3 create virtualenv as named venv*
- For Linux
`virtualenv venv`
- For windows 10
`python -m venv venv`

*Step:4 activate virtualenv*

- For Linux
`source venv/bin/activate`
- For windows 10
`venv\Scripts\activate`

*Step:5 Install packages*
`pip install -r requirements.txt`

*Step:6 Run backend*
`python manage.py runserver`

*Step:6 Test Browser/Server*
`localhost:8000`








