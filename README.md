# A simple Flask web app 
> Creat a minimal website using Flask and deploy to Heroku

A demo <https://hoanvuweb.herokuapp.com/>

More details in the tutorial of [@francescaguiducci](https://medium.com/@francescaguiducci/how-to-build-a-simple-personal-website-with-python-flask-and-netlify-d800c97c283d)

## Installation

1. Clone this repository

```sh
git clone https://github.com/hoanW/simple-Flask-web-app.git
cd simple-Flask-web-app
```

2. Install dependencies

```sh
pip3 install -r requirements.txt
```

## File structure

.
+-- static
|   +-- css
|   |   +-- main.css
|   +-- img
|   +-- favicon.ico
+-- templates
|   +-- home.html
+-- myapp.py
+-- Procfile
+-- requirements

## Deployment

### Previewing the app locally

```sh
python3 myapp.py
```
### Deploy to Heroku

1. Log in to Heroku through Heroku CLI
```sh
heroku login -i
```
2. Connect to your remote Heroku repository
```sh
heroku git:remote -a {your-project-name}
```
3. Commit and push your app to Heroku
```sh
git add .
git commit -m "first commit"
git push heroku master
```
4. Scale your dyno
```sh
heroku ps:scale web=1
```
5. Open your app in the browser
```sh
heroku open
```

## Meta

Hoan Vu – hoanviet.vu@gmail.com

