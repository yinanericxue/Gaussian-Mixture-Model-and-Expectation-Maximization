# Gaussian Mixture Model and Expectation Maximization

![image](https://github.com/yinanericxue/Gaussian-Mixture-Model-and-Expectation-Maximization/assets/102645083/3242d7a5-3e71-4c96-bb7f-66106d660a4c)
#### w, parameters; x, variables

![image](https://github.com/yinanericxue/Gaussian-Mixture-Model-and-Expectation-Maximization/assets/102645083/71984bcd-378e-4c95-93a3-de9968948580)
#### both w and x are variables

![image](https://github.com/yinanericxue/Gaussian-Mixture-Model-and-Expectation-Maximization/assets/102645083/e4eada63-dc86-4425-8558-75c1ad59882f)

![image](https://github.com/yinanericxue/Gaussian-Mixture-Model-and-Expectation-Maximization/assets/102645083/501aa227-3579-4631-8ea8-8578f8242337)

![image](https://github.com/yinanericxue/Gaussian-Mixture-Model-and-Expectation-Maximization/assets/102645083/a319f2af-ba05-487e-afd5-0eb0906825ed)

# Example

#### 100000 families:
#### No child，1000；1 child, 90000；2 children，6000；3 children，3000

#### P(x = 0) = 0.01
#### P(x = 1) = 0.9
#### P(x = 2) = 0.06
#### P(x = 3) = 0.03

![image](https://github.com/yinanericxue/Gaussian-Mixture-Model-and-Expectation-Maximization/assets/102645083/603c2bea-6ab4-43d7-868a-208d92123b7c)

![image](https://github.com/yinanericxue/Gaussian-Mixture-Model-and-Expectation-Maximization/assets/102645083/4c60a9d3-84da-4c33-8888-ee3faf0e466a)

![image](https://github.com/yinanericxue/Gaussian-Mixture-Model-and-Expectation-Maximization/assets/102645083/fefe9428-8e8a-4607-866a-108452c6af67)

![image](https://github.com/yinanericxue/Gaussian-Mixture-Model-and-Expectation-Maximization/assets/102645083/3a5800c7-64c1-4c31-925c-ec65ed7f2b03)

# MLE, Maximum Likelihood Estimation - Regression
![image](https://github.com/yinanericxue/Gaussian-Mixture-Model-and-Expectation-Maximization/assets/102645083/909f738b-f73d-47da-9d15-fda43a2437a1)
![image](https://github.com/yinanericxue/Gaussian-Mixture-Model-and-Expectation-Maximization/assets/102645083/8c99e678-1e98-48de-880f-f7b809eb88df)

#### Method - Least Squares Estimation
#### https://otexts.com/fpp2/least-squares.html
![image](https://github.com/yinanericxue/Gaussian-Mixture-Model-and-Expectation-Maximization/assets/102645083/faeccce9-2701-4607-8ac4-ecb627ce8468)
![image](https://github.com/yinanericxue/Gaussian-Mixture-Model-and-Expectation-Maximization/assets/102645083/33486731-95dc-4f2d-95bb-a4f592244306)


#### Solution 0: Analytical Solution, calculate the result using the algebraic formula
#### Solution 1: Analytical Solution, using matrices

![image](https://github.com/yinanericxue/Gaussian-Mixture-Model-and-Expectation-Maximization/assets/102645083/cce9e36f-cd9c-4504-ab03-2613c4edabd6)

![image](https://github.com/yinanericxue/Gaussian-Mixture-Model-and-Expectation-Maximization/assets/102645083/b7b3fc00-017c-4a81-9bd3-98bcdc6cf892)

![image](https://github.com/yinanericxue/Gaussian-Mixture-Model-and-Expectation-Maximization/assets/102645083/ee9be827-abfb-48db-a67f-b8954055c142)

![image](https://github.com/yinanericxue/Gaussian-Mixture-Model-and-Expectation-Maximization/assets/102645083/2dd33986-230b-4f83-af0f-ac5fc28c8ad6)

#### Solution 2: Gradient Descent  (Stochastic, Mini Batch)
![image](https://github.com/yinanericxue/Gaussian-Mixture-Model-and-Expectation-Maximization/assets/102645083/e815a338-b8b9-41af-888d-a27295708b6a)

![image](https://github.com/yinanericxue/Gaussian-Mixture-Model-and-Expectation-Maximization/assets/102645083/0b682027-a82c-4c94-9a82-bc75ff056001)

![image](https://github.com/yinanericxue/Gaussian-Mixture-Model-and-Expectation-Maximization/assets/102645083/65ed5572-c389-4d2e-a67b-bdfab9b6c816)

![image](https://github.com/yinanericxue/Gaussian-Mixture-Model-and-Expectation-Maximization/assets/102645083/0a0295d8-9a33-4daf-8b89-7dd36cf897ea)


#### Method - Maximum Likelihood Estimation
![image](https://github.com/yinanericxue/Gaussian-Mixture-Model-and-Expectation-Maximization/assets/102645083/02590865-d107-449c-a5bd-9a2dda2afc2e)

#### Sample PDF -  (xi,yi)
![image](https://github.com/yinanericxue/Gaussian-Mixture-Model-and-Expectation-Maximization/assets/102645083/1d3d3b05-b0a2-4fef-b804-82772df78965)

#### MLE
![image](https://github.com/yinanericxue/Gaussian-Mixture-Model-and-Expectation-Maximization/assets/102645083/9fc9f5b7-58f3-4f22-b903-f6dce7172b5e)

#### Log MLE
![image](https://github.com/yinanericxue/Gaussian-Mixture-Model-and-Expectation-Maximization/assets/102645083/ccfe40dc-844b-4998-a92a-aa2686d007be)
![image](https://github.com/yinanericxue/Gaussian-Mixture-Model-and-Expectation-Maximization/assets/102645083/939cd293-35b6-49ae-a2eb-db48fd20a55a)

#### Least Squares
![image](https://github.com/yinanericxue/Gaussian-Mixture-Model-and-Expectation-Maximization/assets/102645083/c059cb69-c284-4a4f-9f0e-2f5244150da5)

![image](https://github.com/yinanericxue/Gaussian-Mixture-Model-and-Expectation-Maximization/assets/102645083/3a2a4c56-26a5-47eb-9b49-b0b115e2e14b)


#### Maximum Likelihood Estimation - Classification

#### Sigmod
<img width="350" alt="image" src="https://github.com/yinanericxue/Gaussian-Mixture-Model-and-Expectation-Maximization/assets/102645083/48e7b07c-944c-4736-a826-912a557d0e9e">


#### Model ( 0 or 1 )
![image](https://github.com/yinanericxue/Gaussian-Mixture-Model-and-Expectation-Maximization/assets/102645083/2045a529-f10a-4f0f-bb8a-ea3b72d71bf6)
![image](https://github.com/yinanericxue/Gaussian-Mixture-Model-and-Expectation-Maximization/assets/102645083/7fd1656d-95af-4108-b7a6-dc30ce627ed3)
