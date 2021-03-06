## Control Of Epidemic Spreads Via Testing And Lock-Down

[Subhonmesh Bose](https://ece.illinois.edu/about/directory/faculty/boses),
[Sebastian Souyris](https://giesbusiness.illinois.edu/profile/sebastian-souyris),
[Ujjal Kumar Mukherjee](https://giesbusiness.illinois.edu/profile/ujjal-mukherjee),
[Anton Ivanov](https://giesbusiness.illinois.edu/profile/anton-ivanov),
[Sridhar Seshadri](https://giesbusiness.illinois.edu/profile/sridhar-seshadri),
[Albert C. England III](https://providers.osfhealthcare.org/provider/Albert+C.+England/1465363),
[Yuqian Xu](https://sites.google.com/site/lillianyuqian/home)

**Accepted for presentation at, and publication in the proceedings of, the 2021 IEEE Conference on Decision and Control (CDC).**

Testing and lock-down are interventions that can combat the spread of an infectious disease. Testing is a targeted instrument that permits the isolation of infectious individuals. Lock-down, on the other hand, is blunt and restricts the mobility of all people. In this paper, we present a compartmental epidemic model that accounts for the impact of lock-down and different kinds of testing, motivated by the nature of the ongoing COVID-19 outbreak. We consider the testing of symptomatic, contact traced, and randomly chosen asymptomatic populations. Using the model, we first characterize static mobility levels and testing requirements that can dampen the spread asymptotically. We then characterize a threshold-type optimal lock-down policy that minimizes the social impact of an epidemic, modeled via a sum of infection and lockdown costs. Our results are contextualized with realistic parameter values for COVID-19.

Download the [paper](http://boses.ece.illinois.edu/files/COVID19_testlockdown.pdf).

Access the [code](/Notebooks/lockdown_cdc.ipynb).

HEART Group [home page](https://heart-analytics.github.io/Home/).


![Figure 1 Our compartmental model](Figures/supr.png)
**Figure 1.** Our SUPR compartmental model.

![Figure 2](Figures/fig2.png)
**Figure 2.** Numerical experiments with *T = 120* days, *??<sub>I</sub> = 0.5, ??<sub>S</sub> = 0.08, ??<sub>0</sub> = 0.9, ?? = 1/13, ?? = 15, F<sub>min</sub>= 0.6* and *U<sup>0</sup> = 10<sup>-4</sup>*. Plot on the left shows the optimal infection threshold *??<sup>t</sup>*. Plot on the right depicts the costs *J* obtained by implementing the optimal control policy with a delay.

![Figure 3](Figures/fig3.png)
**Figure 3.** Plot portrays *U<sup>t</sup>* with and without contact tracing for two different values of *Z*.
