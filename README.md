### A websocket example using channels: chat room

#### create python environment
```
conda create --name web_dev python=3.9
conda activate web_dev
pip install -r requirements.txt
```
### create database
```
python manage.py migrate
```
#### run redis server
```
docker run --rm -p 6379:6379 redis:7
```
#### run django server
```
python3 manage.py runserver
```
### open web browser
open the url: http://127.0.0.1:8000/chat/
