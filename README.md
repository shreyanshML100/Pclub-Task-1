**Analysis for various Cost Functions:**

 The plots of the cost functions v/s the number of iterations are as following:
 
 a.)
 
 ![image](https://user-images.githubusercontent.com/84093261/130113152-72748a9b-f816-4e20-9024-1709ccc46e28.png)

 b.)
 
 ![image](https://user-images.githubusercontent.com/84093261/130113261-dda39f2f-d00c-4efe-ac0a-4b4a031ca0f3.png)

 c.)
 
 ![image](https://user-images.githubusercontent.com/84093261/130113353-820a3dd3-5c57-4ad4-beb0-322b04a1ffef.png)

 d.)
 
 ![image](https://user-images.githubusercontent.com/84093261/130113435-379b2852-dc27-477f-b5c5-dd2792f436ae.png)
  
  
 **Analysis of the different Loss functions:**
 
 1. For the different Loss Functions the appropriate Learning Rates in Regression should decrease as the Degree over the Loss Function increases.If the same learning rate is used to train the parameters in all the Cost functions then it may lead to some of the cost functions of the higher degree to diverge.

 2. The absolute value of loss function does not imply whether the Regression has fit the curve better or not. It should be the Ratio between the *final cost value* and the       *initial cost function value* which should be reduced to check whether the parameters fit well or not.For Example, In case (d.) 10^5 value of the cost function might be considered good while in case (a.) such a value would mean that the parameters have not fit well. Hence the ratio must be considered when checking whether the parameters have fit well or not.
   
 3. The plots of the Curves which have been fitted using Regression (using Trained Parameters) are-

a.)

![image](https://user-images.githubusercontent.com/84093261/130116467-ed229694-1a06-4b4a-b99c-2414fa10c205.png)

b.)

![image](https://user-images.githubusercontent.com/84093261/130116546-2233a16d-e5f7-4990-b2b0-1fb10ff67c76.png)

c.)

![image](https://user-images.githubusercontent.com/84093261/130116586-a79858ef-a064-4ee2-bcfb-a97f5cba5b07.png)

d.)

![image](https://user-images.githubusercontent.com/84093261/130116617-7fcf0ad0-bc59-4b5d-9311-3a4db21ffc86.png)
