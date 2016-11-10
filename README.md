# gaussian_policy
continuous action space. 



Previously it was Exp(linear) parametric form. Now it is a Exp(quadratic) form. It will give a better approximation than Bolzman machine. Interesting. It is different. Bolzman machine specifies the probability of (s, a) using state-action feature of (s, a). Here mu_s is based on state-feature and mu_s has dimensions of action variables. If you stack Bolzman's pi(s, a) for all the actions, it also becomes a vector. So bolzman machine enumerates all the probablities for the actions. 

Even you can just improve Bolzman machine to the second order. That is another idea of using Gaussian. Still interesting. It can improve Bolzman Machine. Let's do another paper on this. Let's take sigma to be identity. mu will be theta. Is it better than Bolzman? You don't have to normalize. What about \sigma? Learn it? Does it add to complexity?

What about 1D? The action variable is only 1D and continuous. It is still advantageous than Bolzman in terms of approximation power, and continuous action. 

Just study a 1D case. 

wait. the pdf of gaussian does not correspond to pi. It is actually the CDF. The CDF of Gaussian can be approximated by the sum of infinitely polynormials. 

[Gaussian policy is good for continuous action space](http://home.deib.polimi.it/restelli/MyWebSite/pdf/rl7.pdf)

[paper](http://www.vision.cs.chubu.ac.jp/MPRG/C_group/C060_yamashita2014.pdf)

[2011](https://users.ics.aalto.fi/praiko/papers/nips11Cho.pdf)



