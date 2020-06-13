FROM python:3.8.2
RUN pip install --upgrade pip && \
    pip install numpy==1.18.2 scipy==1.4.1 scikit-learn==0.22.2.post1 \
                numba==0.48.0 networkx==2.4
RUN mkdir /opt/atcoder
WORKDIR /opt/atcoder