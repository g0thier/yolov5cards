# yolov5cards

#### Model from :
[Yolo v5](https://github.com/ultralytics/yolov5)
 
__In Terminal__
*change path as you need*

Ininial instalation :

    pip3 install -r requirements.txt

Creation new yolo model :

    python train.py --data /Users/Stickers/gauthier/yolov5/data/PlayingCards/data.yaml  --weights '' --cfg yolov5s.yaml --img 640 --batch 16 --epochs 100 --name yolov5m_results

Utilisation model :

    python3 detect.py --weights /Users/gauthier/Documents/GitHub/yolov5cards/runs/train/yolov5m_results5/weights/best.pt --img 416 --conf 0.001 --source /Users/gauthier/Documents/GitHub/yolov5cards/Cards
