futurecms project
=======================

a cms base on [Wagtail CMS](https://github.com/wagtail/wagtail) for offical web or blog or shop son on.

# Installation

#### Dependencies

* Python 3.6, 3.7 or 3.8
* [Wagtail](https://github.com/wagtail/wagtail)

###  Installation

Once you've installed the necessary dependencies run the following commands:

```bash
    pip3 install wagtail
    git clone https://github.com/stop-coding/futurecms.git
    cd futurecms
    python3 manage.py migrate
```

###  add superuser
firstly, it need create a superuser to manage these page which they will publish or others.

```bash
    python3 manage.py createsuperuser
```
input your username and password

###  run
you can run site for testing if it ok.default command, then bind 127.0.0.1:8000.

```bash
    python3 manage.py runserver
```
or
```bash
    python3 manage.py runserver 0.0.0.0:8000
```

others
----------------






