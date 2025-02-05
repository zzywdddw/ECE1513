# Lecture 1  
<strong>unsupervised learning</strong> - data samples are not labeled, model capture the pattern hidden in data Example: clustering, dimensionality reduction, distribution learning.  
<strong>supervised learning</strong> - data samples are labeled, model describes the relation between data samples and their labels  
Example: classification, regression  
<strong>reinforcement learning</strong> - data samples are series of actions, states and rewards. We are looking for optimal policy that maximizes future returns.  
Example: playing games, control robots
<br>  
<br>  
<strong>K-mean Clustering Algorithm</strong>  
![image](https://github.com/user-attachments/assets/ab4b0f05-bde8-4227-b07e-19c2d941b948)  
![image](https://github.com/user-attachments/assets/075c588d-fae5-4533-bc52-0d4a5c3027a4)  
![image](https://github.com/user-attachments/assets/24a66ad7-4e11-4851-b94c-c4a3adc9c07a)  
![image](https://github.com/user-attachments/assets/a973c7d8-1025-4caf-b207-a52f81e15c23)  
![image](https://github.com/user-attachments/assets/843d62d0-fde9-4ea9-9072-d08ead19c2c8)  
![image](https://github.com/user-attachments/assets/dc5a98ec-6548-4065-89c5-e5ee5e0e17c1)  
<br>  

<strong>Soft K mean</strong>  
Soft K -means clustering treats the cluster assignments as probability distributions over the clusters.  
![image](https://github.com/user-attachments/assets/15b245a4-21ab-4754-a638-fc48bad10fb5)  
<br>  
<br>  
<br>  
# Lecture 2  
![image](https://github.com/user-attachments/assets/af4318ae-7f9f-4acc-b4b2-3b087f708911)  
![image](https://github.com/user-attachments/assets/be2766e8-d014-4d14-9816-915191f3fba8)  
<br>  
Random variables x and y are independent if P(x,y) = P(x)P(y)  
i.i.d. sequence: X1,...,Xn are independent and identically distributed if they are independent and have the same distribution (same mean and standard deviation)  
![image](https://github.com/user-attachments/assets/2517f346-60fb-4ff7-bee0-777420fcc845)  
![image](https://github.com/user-attachments/assets/f566227d-8c39-4e09-97b2-eb8ce80c2a57)  
![image](https://github.com/user-attachments/assets/aef2faf1-5f37-4ef9-829d-0da3de9a83ae)  
<br>  
<strong>Probability Mass Function</strong>  
PMF describes the probability of each specific outcome of a discrete random variable.  
![image](https://github.com/user-attachments/assets/8ee93400-75dc-46cf-9fe5-1fb81f7914c2)  
Examples:  If x is the result of rolling a fair 5-sided die:  
P(X=x) = 1/6, x = 1,2,3,4,5,6 or = 0 otherwise  
<br>  
<strong>Probability Density Function</strong>  
PDF describes the likelihood if a continuous random variable taking on a value within an interval. Unlike PMF, it does not give direct probabilities but rather a density  
![image](https://github.com/user-attachments/assets/ae22fa7b-5bc1-43bd-81e6-549bee8e86a6)  
![image](https://github.com/user-attachments/assets/0b94a026-db7c-4af6-81a3-b22bd88137e9)  
<br>  
<strong>Gaussian Distribution</strong>  
![image](https://github.com/user-attachments/assets/73585695-713b-4fa8-8604-68ca6308fb0e)  
Why Gaussian?  
1. Many processes in nature are approximately Gaussian
2. Sum of large enough independent random objects tends to a Gaussian object
3. Superposition of Gaussians can describe a large class of distributions
<br>

<strong>Maximum Likelihood Estimation (MLE)</strong>
S(μ,Σ) is the log of the likelihood function normalized by the number of samples 𝑁. Taking the log of the likelihood simplifies calculations, especially for large datasets, and normalization makes it more manageable to interpret
![image](https://github.com/user-attachments/assets/48ca2ef9-d103-4092-bec3-1814a3e77bd9)  
<br>  
<br>  
<br>  
# Lecture 3  
![image](https://github.com/user-attachments/assets/12f2d2f3-21b2-4bda-b228-cecce9196f4a)  
![image](https://github.com/user-attachments/assets/ab1fbad7-f270-4648-ab0f-909ae1fe2814)  
![image](https://github.com/user-attachments/assets/f8ca95da-7006-4898-858a-97f829252c74)  
![image](https://github.com/user-attachments/assets/3bb19761-932e-40a2-beb6-86d573d0d0f0)  
![image](https://github.com/user-attachments/assets/79f2dc17-95da-4607-9550-145fc3329433)  
![image](https://github.com/user-attachments/assets/ffc19897-effc-4231-9bf5-320e84310663)  
![image](https://github.com/user-attachments/assets/948b1fb4-523d-47d1-acaa-937e32f637ac)






























