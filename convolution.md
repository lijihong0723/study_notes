# 卷积入门

## 基本定义

两个函数$f(x)$和$g(x)$，其卷积定义如下：

连续形式的定义
$$
(f*g)(x) = \int_{-\infty}^{+\infty} f(\alpha) g(x - \alpha) \text{d} \alpha
$$
离散形式的定义
$$
(f * g)(x) = \sum_{\alpha = -\infty}^{+\infty} f(\alpha)g(x - \alpha)
$$
