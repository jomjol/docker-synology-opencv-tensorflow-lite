FROM python:3.7

WORKDIR /

COPY ./wheels ./wheels
RUN pip install --no-cache-dir ./wheels/tflite_runtime-2.1.0.post1-cp37-cp37m-linux_x86_64.whl
RUN pip install --no-cache-dir numpy Pillow opencv-python
RUN rm -r ./wheels