
pip install -r requirements.txt

// python src/align_dataset_mtcnn.py  Dataset/FaceData/raw Dataset/FaceData/processed --image_size 160 --margin 32  --random_order --gpu_memory_fraction 0.25

python src/face_rec_cam.py 

python src/face_rec.py --path Videos/thanhhuongvd.mp4
