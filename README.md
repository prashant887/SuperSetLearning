python3.9 -m venv superset_env


sudo CFLAGS=-stdlib=libc++ pip3 install python-geohash
sudo CFLAGS=-stdlib=libc++ pip3 install superser

downgrade
pip install WTForms==2.3.3
pip install cryptography==38.0.3


Pip Freeze

aiohttp==3.8.3
aiosignal==1.3.1
alembic==1.9.1
amqp==5.1.1
apache-superset==2.0.1
apispec==5.2.2
async-generator==1.10
async-timeout==4.0.2
attrs==22.2.0
Babel==2.11.0
backoff==2.2.1
billiard==3.6.4.0
bleach==3.3.1
Brotli==1.0.9
cachelib==0.4.1
celery==5.2.7
certifi==2022.12.7
cffi==1.15.1
charset-normalizer==2.1.1
click==8.1.3
click-didyoumean==0.3.0
click-plugins==1.1.1
click-repl==0.2.0
colorama==0.4.6
convertdate==2.4.0
cron-descriptor==1.2.32
croniter==1.3.8
cryptography==38.0.3
deprecation==2.1.0
dnspython==2.2.1
email-validator==1.3.0
exceptiongroup==1.1.0
Flask==2.2.2
Flask-AppBuilder==4.2.0
Flask-Babel==2.0.0
Flask-Caching==1.11.1
Flask-Compress==1.13
Flask-JWT-Extended==4.4.4
Flask-Login==0.6.2
Flask-Migrate==4.0.1
Flask-SQLAlchemy==2.5.1
flask-talisman==1.0.0
Flask-WTF==1.0.1
frozenlist==1.3.3
func-timeout==4.3.5
geographiclib==2.0
geopy==2.3.0
graphlib-backport==1.0.3
gunicorn==20.1.0
h11==0.14.0
hashids==1.3.1
hijri-converter==2.2.4
holidays==0.14.2
humanize==4.4.0
idna==3.4
importlib-metadata==6.0.0
isodate==0.6.1
itsdangerous==2.1.2
Jinja2==3.1.2
jsonschema==4.17.3
kombu==5.2.4
korean-lunar-calendar==0.3.1
Mako==1.2.4
Markdown==3.4.1
MarkupSafe==2.1.1
marshmallow==3.19.0
marshmallow-enum==1.5.1
marshmallow-sqlalchemy==0.26.1
msgpack==1.0.4
multidict==6.0.4
numpy==1.22.1
outcome==1.2.0
packaging==23.0
pandas==1.3.5
parsedatetime==2.6
pgsanity==0.2.9
Pillow==9.4.0
polyline==1.4.0
prison==0.2.1
prompt-toolkit==3.0.36
pyarrow==5.0.0
pycparser==2.21
pydruid==0.6.5
PyJWT==2.6.0
PyMeeus==0.5.12
pyparsing==3.0.9
pyrsistent==0.19.3
PySocks==1.7.1
python-dateutil==2.8.2
python-dotenv==0.21.0
python-geohash==0.8.5
pytz==2022.7
PyYAML==6.0
redis==4.4.1
requests==2.28.1
selenium==4.7.2
simplejson==3.18.1
six==1.16.0
slackclient==2.5.0
sniffio==1.3.0
sortedcontainers==2.4.0
SQLAlchemy==1.3.24
SQLAlchemy-Utils==0.37.9
sqlparse==0.3.0
tabulate==0.8.9
trio==0.22.0
trio-websocket==0.9.2
typing-extensions==3.10.0.2
urllib3==1.26.13
vine==5.0.0
wcwidth==0.2.5
webencodings==0.5.1
Werkzeug==2.2.2
wsproto==1.2.0
WTForms==2.3.3
WTForms-JSON==0.3.5
yarl==1.8.2
zipp==3.11.0


superset run -p 8088 --with-threads --reload --debugger

http://localhost:8088/
