A simple flask app to remove the background of an image with [Rembg](https://github.co m/danielgatis/rembg)

Watch the [tutorial](https://youtu.be/cw34KMPSt4k) on YouTube

## Run it

```
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python app.py
```

run the docker: 

```
docker build -t my-rembg-app .
docker run -d -p 8080:5100 --name my-rembg-app my-rembg-app
```