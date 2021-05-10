# Syllabus: Econometrics II 

**Time:** Spring 2021; Mondays 9am; Wednesdays 11:15am

**Location:** Seminari C

**Faculty:** Minyoung Rho (minyoung.rho@uab.cat)

**Teaching Assistance:** Jacek Barszczewski (jacek.barszczewski@gmail.com)


**Course Webpage:** https://github.com/minyoungrho/Econometrics2

## Description:
In this course, we study the estimation of structural economic models. Economic theory implies the structure of the observed variables in the data, which we can exploit to estimate the parameters of the model. We focus on extremum estimators (EE): maximum likelihood estimator (MLE), generalized method of moments (GMM), and etc. For a given estimator, we establish the large sample property (consistency and asymptotic normality) under certain conditions, and test hypotheses about the parameters of interest. 

We also study other advancements in modern Econometrics such as  nonparmetric estimation, which has no misspecification error but has a slower rate of convergence compared to parametric estimation, bayesian methods and quantile regressions.

## Programming:
In this course, we will use [the Julia Programming Language](https://julialang.org/) to study empirical counterparts to the theories introduced.

## Course Schedule

**Lectures:**

| Date | Keywords* |  Content | Reading  |
|---|:---|:---|:---|
| April 6 | [EE](https://github.com/minyoungrho/Econometrics2/blob/main/lectures/EE.ipynb) | Introduction; Consistency  | Hayashi, 7.1-7.2  |   
| April 12 | [EE](https://github.com/minyoungrho/Econometrics2/blob/main/lectures/EE.ipynb) | Asymptotic Normality & Hypothesis Testing | Hayashi, 7.3-7.4  |
| April 14 | [MLE](https://github.com/minyoungrho/Econometrics2/blob/main/lectures/MLE.ipynb) | Examples | Cameron and Trivedi, Ch. 5; [Creel](https://github.com/mcreel/Econometrics/blob/master/econometrics.pdf), Ch.15  | 
| April 19 | [GMM](https://github.com/minyoungrho/Econometrics2/blob/main/lectures/GMM.ipynb) | Examples | [Creel](https://github.com/mcreel/Econometrics/blob/master/econometrics.pdf), Ch.16  | 
| April 21 | [NumOp](https://github.com/minyoungrho/Econometrics2/blob/main/lectures/NumOp.ipynb) | Search, Derivative Based Methods | [Creel](https://github.com/mcreel/Econometrics/blob/master/econometrics.pdf), Ch.12  | 
| April 26 | [NumOp](https://github.com/minyoungrho/Econometrics2/blob/main/lectures/NumOp.ipynb) | Nonlinear Optimization; Constrained Optimization | [Creel](https://github.com/mcreel/Econometrics/blob/master/econometrics.pdf), Ch.12  | 
| April 28 | [Nerlove](https://github.com/minyoungrho/Econometrics2/blob/main/lectures/Nerlove.ipynb) | OLS, MLE, GMM, Restricted Optimization, and Hypothesis Testing | [Creel](https://github.com/mcreel/Econometrics/blob/master/econometrics.pdf), Ch. 6   | 
| May 3 | [Bayesian](https://github.com/minyoungrho/Econometrics2/blob/main/lectures/Bayesian.ipynb) | Prior, Posterior, Bayes Rules, and Markov chain Monte Carlo (MCMC) | [Creel](https://github.com/mcreel/Econometrics/blob/master/econometrics.pdf), Ch. 18; [Mikusheva’s MIT OpenCourseWare notes](https://ocw.mit.edu/courses/economics/14-384-time-series-analysis-fall-2013/lecture-notes/) Lectures 23-25; Rossi et al. (2005) Chapters 2 & 3  | 
| May 5 | [Bayesian](https://github.com/minyoungrho/Econometrics2/blob/main/lectures/Bayesian.ipynb) | Metropolis-Hastings algorithm and Gibbs Sampling | [Creel](https://github.com/mcreel/Econometrics/blob/master/econometrics.pdf), Ch. 18; [Mikusheva’s MIT OpenCourseWare notes](https://ocw.mit.edu/courses/economics/14-384-time-series-analysis-fall-2013/lecture-notes/) Lectures 23-25; Rossi et al. (2005) Chapters 2 & 3  | 
| May 10 | [TimeSeries](https://github.com/minyoungrho/Econometrics2/blob/main/lectures/TimeSeries.ipynb) | AR, MA, ARCH, and GARCH | [Creel](https://github.com/mcreel/Econometrics/blob/master/econometrics.pdf), Ch. 17 | 


*Keywords (or corresponding file name in [lectures folder](https://github.com/minyoungrho/Econometrics2/tree/main/lectures)): 
  - extremum estimators (EE)
  - maximum likelihood estimator (MLE)
  - generalized method of moments (GMM)
  - numerical optimization (NumOp)



**TA:**
[Contents](https://drive.google.com/drive/folders/1fxlpdpmILn8Dj9zYJe7VzHwOdA4nUW6s?usp=sharing)
| Date | Content |
|:---:|:---|
| April 9 | Introduction to Julia | 
| April 16 | Consistency of the LS; Asymptotic Normality of MLE | 
| April 22 | Consistency and the Asymptotic Normality of IV |
| April 30 | Solutions to Problem Set 1 |


**Problem Sets:**
| Problem Set # | Link |Assign Date |  Due Date |
|:---:|:---|:---|:---|
| 1 | [PS1](https://github.com/minyoungrho/Econometrics2/blob/main/ps/ps1.ipynb);[PDF](https://github.com/minyoungrho/Econometrics2/blob/main/ps/ps1.pdf) | April 12 | April 26 |
| 2 | [PS2](https://github.com/minyoungrho/Econometrics2/blob/main/ps/ps2.ipynb);[PDF](https://github.com/minyoungrho/Econometrics2/blob/main/ps/ps2.pdf) | April 26, last updated May 1 | May 10 |
| 3 | [PS3](https://github.com/minyoungrho/Econometrics2/blob/main/ps/ps3.ipynb);[PDF](https://github.com/minyoungrho/Econometrics2/blob/main/ps/ps3.pdf) | May 10 | May 24 |

## Grading: 
- 3 Problem sets (60%)
- Final exam (40%)

## References
The references for the course materials will be updated throughout the course.
- Creel. https://github.com/mcreel/Econometrics/blob/master/econometrics.pdf
- Hayashi, F. (2000). *Econometrics.*
- Amemiya, T. (1985). *Advanced Econometrics.*
- Davidson, R., MacKinnon, J. G. (2004). *Econometric theory and methods.*
- Cameron, A.C. and Trivedi, P.K. (2005). *Microeconometrics: methods and applications.*
- Rossi, P. E., Allenby, G. M. and McCulloch, R. (2005). *Bayesian Statistics and Marketing*
- [Mikusheva’s MIT OpenCourseWare notes](https://ocw.mit.edu/courses/economics/14-384-time-series-analysis-fall-2013/lecture-notes/)
- Victor Chernozhukov and Han Hong. An MCMC approach to classical estimation. Journal of
Econometrics, 115(2):293–346, 2003. doi: 10.1016/s0304-4076(03)00100-3. URL: http://dx.doi.org/10.1016/s0304-4076(03)00100-3.

- https://quantecon.org/
