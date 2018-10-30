# Image Clustering by Complex Network Representation

Here we gona detect some Scenes from random video and choose an frame to represent it's content.

![from you tube](youtube_BrooklynNineNine.jpg)

[ Sample video here!](https://youtu.be/ffyKY3Dj5ZE) 

## 1. Extract frames from fideo...

* OpenCV

## 2. Extract fieatures from frames...

* VGG16

## 3 Represent into complex networks...

* nodes by image name

* edges weights by cosine similarity

## 4. Cluster frames into scenes by community detection...

* Louvain

## 4. Find the most frequently shown scene class...

* Just Counting

## 5. Choose the by mainframe from the most frequent scene!

* degree centrality

![Chosen frame](data/image_1232)