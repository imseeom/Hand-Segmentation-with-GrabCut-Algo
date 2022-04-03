# Hand Segmentation with GrabCut Algorithm #
Implements GrabCut algorithm to segment images
The overall procedure goes:
1) Load the images:  
![image](https://user-images.githubusercontent.com/81301185/161442918-1f1ce468-b137-4096-957d-c644910c468e.png)
2) Draw a bounding box as input for the GrabCut algorithm
3) Initialise the GrabCut algorithm with the bounding box drawn  
![image](https://user-images.githubusercontent.com/81301185/161442935-6895d250-cb86-48c7-9f8c-959bc5a98356.png)
4) Note that the output image will be partially segmented and is imperfect. Draw a custom mask on the image for further segmentation
![image](https://user-images.githubusercontent.com/81301185/161442981-6b68bfd6-ce1d-4307-bc90-72f924a856cd.png)
**Final Output**  
![image](https://user-images.githubusercontent.com/81301185/161443000-8353bb8c-3049-410b-8812-c42bf0eb075d.png)
5) Save the image if satisfied, otherwise repeat the touch up process
