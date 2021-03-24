In Stochastic Volatility Model, I'm given

$$
G(v, y, z)=\frac{1}{u \sqrt{2 \pi\left(1-\rho^{2}\right) y}} \exp \left(-\frac{\left(\log \left(\frac{u}{S_{0}}\right)-r T+\frac{y}{2}-\rho\left(g(v)-g\left(v_{0}\right)-z\right)\right)^{2}}{2\left(1-\rho^{2}\right) y}\right)
$$

and inﬁnitesimal generator

$$
(\mathcal{L} G)(v, y, z)=\mu(v) \frac{\partial G(v, y, z)}{\partial v}+\frac{1}{2} \sigma^{2}(v) \frac{\partial^{2} G(v, y, z)}{\partial v^{2}}+m^{2}(v) \frac{\partial G(v, y, z)}{\partial y}+h(v) \frac{\partial G(v, y, z)}{\partial z}
$$

So to simulate the stock price in SV model, I just need to choose desired order $J$, and plug them into Ito-Taylor formula...

