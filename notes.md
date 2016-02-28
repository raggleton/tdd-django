# Some notes

**Start a server:**

```
python3 manage.py runserver
```

**Run unit tests** (in `lists/test.py`):

```
python3 manage.py test lists
```

**Run functional tests** (in `functional_tests/tests.py`):

```
python3 manage.py test functional_tests
```

**Cleanup & remake database**

```
rm db.sqlite3
python3 manage.py migrate --noinput
``` 
