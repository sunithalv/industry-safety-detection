# Industry-Safety-Detection-using-YOLO-v7

In this project a detection system is created uisng Computer Vision using YOLO v7 to monitor,track and enforce workers to wear the necessary protective gears in industries.The detection system is designed and modelled to take real time of the personnel as input and determine the 5 segments - helmet,gloves,jacket,goggles and footwear before entering the workplace.

## 🧑‍💻 How to setup
create fresh conda environment 
```python
conda create -p venv python=3.7 -y
```
activate conda environment
```python
conda activate venv/
```
Install requirements
```python
pip install -r requirements.txt
```
Run the web app
```python
python app.py
```
To launch web page
```python
http://127.0.0.1:8080/
```

**<center> NOTE: upload the photos with frontal face. </center>**

## 🧑‍💻 Tech Used
1. computer vision
2. yolov7 
3. openCV 
4. Docker
5. AWS S3
6. AWS ECR
7. AWS EC2