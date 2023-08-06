# Lisa's blog

Django blog, server side.

## Launch

You should already have Python 3 installed to run the blog.

- Download the code
- Install the dependencies with the command `pip install -r requirements.txt`
- Start the server with the command `python3 manage.py runserver`

After that go to [127.0.0.1:8000](http://127.0.0.1:8000), you will see the home page.

## Environment variables

Some of the project settings come from environment variables. To define them, create a `.env` file next to `manage.py` and write the data there in this format: `VARIABLE=value`.

**These settings are not required** to start the project, the values are already set by default.

The following variables are available:
- `DEBUG` - debug mode. Set `True` to see debug information in case of an error. Turns off with `False` value.
- `SECRET_KEY` - the secret key of the project. For example: `erofheronoirenfoernfx49389f43xf3984xf9384`.
- `ALLOWED_HOSTS` - see [Django documentation](https://docs.djangoproject.com/en/3.1/ref/settings/#allowed-hosts).
- `STATIC_URL` - the default is `'/static/'`. [What is STATIC_URL](https://docs.djangoproject.com/en/3.0/ref/settings/#std:setting-STATIC_URL).
- `STATIC_ROOT` - the default is `'None'`, i.e. the current folder. [What is STATIC_ROOT](https://docs.djangoproject.com/en/3.0/ref/settings/#std:setting-STATIC_ROOT).
- `MEDIA_URL` - defaults to `'/media/'`. [What is MEDIA_URL](https://docs.djangoproject.com/en/3.0/ref/settings/#std:setting-MEDIA_URL).
- `MEDIA_ROOT` - The default is `'media'`. [What is MEDIA_ROOT](https://docs.djangoproject.com/en/3.0/ref/settings/#std:setting-MEDIA_ROOT).

## Project Goals

The code is written for educational purposes - it's a lesson in a course on Python and web development on the [Devman](https://dvmn.org).
