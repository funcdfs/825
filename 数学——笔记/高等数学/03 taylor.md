
![image.png](https://raw.githubusercontent.com/psychonaut1f/mac/main/2025/20250305223006583.png)

## 等价无穷小

$$
\ln(1+x)\sim x \qquad 推论： \ln u\sim u-1(u\to {1})
$$  

$$
\sqrt{ 1+x }-\sqrt{ 1-x }\sim x
$$  

$$
(1+ax)^{b}-1\sim abx
$$  

$$
a^{x}-1=e^{x\ln a}-1\sim x\ln a
$$  

$$
1-\cos ^{\alpha}x\sim \cfrac{\alpha}{2}x^{2}
$$  

$$
(1+x)^{1/x}-e\sim -\cfrac{e}{2} x(x\to 0^{+})
$$

## taylor

泰勒研究高阶导问题：函数值 + 一阶导乘以 x- 函数值，+ 二阶导除以二的阶乘乘以 x- 函数值的平方  
通常情况下，都加拉格朗日余项，只有在 $x\to x_{0}$ 的时候才加佩亚诺余项 $O(x-x_{0})^{n}$

![SmartSelect_20240321_134313_Nebo.jpg](https://raw.githubusercontent.com/psychonaut1f/b/main/img/202403211343760.jpg)

## 补充 taylor：

反双曲正弦函数：

$$
\ln(x+\sqrt{ 1+x^{2} })=x-\frac{1}{6}x^{3}+o(x^{3})
$$

三角函数的平方：

$$
(\sin x)^{2}=x^{2}-\frac{1}{3}x^{4}+o(x^{4})
$$

$$
(\cos x)^{2}=1-x^{2}+\frac{1}{3}x^{4}+o(x^{4})
$$
