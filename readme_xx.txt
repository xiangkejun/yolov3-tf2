在 python3 下测试
测试

python3 convert.py
python3 convert.py --weights ./data/yolov3-tiny.weights --output ./checkpoints/yolov3-tiny.tf --tiny

python detect.py --image ./data/meme.jpg
python3 detect.py --weights ./checkpoints/yolov3-tiny.tf --tiny --image ./data/street.jpg


python3 detect_video.py --video ./1.avi --weights ./checkpoints/yolov3-tiny.tf --tiny
