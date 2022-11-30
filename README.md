# Face Alignment for Facial Recognition

Face Alignment is the technique in which the image of the person is rotated according to the angle of the eyes.  This technique is actually used as a part of the pipeline process in which facial detection is done using the image.

Suppose if the person’s eyes in the image are at an x angle (x!=180 degrees) with reference to the frame of the image then this technique will rotate the image according to the angle where the x angle will be equal to 180 degrees with reference to the image frame.

![image](https://user-images.githubusercontent.com/11797397/204784550-02e286bb-4002-4866-9c12-694b3868dfa3.png)


Now the angel x can be easily calculated from the triangle formed by the eyes and the referenced frame using trigonometry. By applying the <b>Euclidean distance</b> we can get the value of the angle x.

 <b>cos(x) = (b2+ c2– a2 ) / (2bc)</b>
 
 ![image](https://user-images.githubusercontent.com/11797397/204784766-21436e68-78c3-430b-a596-5653272bbde2.png)

![image](https://user-images.githubusercontent.com/11797397/204784824-b1ae36a7-9eb7-4b77-9de8-d2e2108568e7.png)
