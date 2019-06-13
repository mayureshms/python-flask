Flast python deployment 

To create the image 

$ docker build -t pucsd:latest .

To create the container

$ docker run -itd -p 5000:5000 pucsd:latest

Run the URL in browser

http://localhost:5000/
