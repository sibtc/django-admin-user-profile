# Django Admin User Profile

Example used in the blog post [How to Add User Profile To Django Admin](https://simpleisbetterthancomplex.com/tutorial/2016/11/23/how-to-add-user-profile-to-django-admin.html)

## Running Locally

```bash
git clone https://github.com/sibtc/django-admin-user-profile.git
```

```bash
pip install -r requirements.txt
```

```bash
python manage.py migrate
```

```bash
python manage.py createsuperuser
```

```bash
python manage.py runserver
```

Now open the Django admin in a web browser: 127.0.0.1:8000/admin/
