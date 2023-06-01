- Git clone repository

```
git clone https://github.com/nmcvanson/ObjectDetection.git
```
- Go to clone folder
- Install the dependencies
```
pip install -r requirements.txt
```

- Run
```
python predict.py model='yolov8n.pt' source='0'
```

(Выбрать тип обученной модели: ```yolov8n.pt```, ```yolov8s.pt```,``` yolov8m.pt```, ```yolov8l.pt```, ```yolov8x.pt``` (точность увеличивается но скорость уменьшается))

- Результат сохраняется в папке "runs"