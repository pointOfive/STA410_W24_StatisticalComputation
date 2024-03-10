# STA410_W24_StatisticalComputation
Third re-build of STA410 Statistical Computation / STA2102 Computational Techniques in Statistics

## Course Topics

1. Sampling: Inverse CDF, Rejection, and Importance Sampling
    1. [Lecture Notebook](Week1/STA410_W24_Week1_Lecture_Sampling.ipynb)
    2. [Coding Demo: `python` speed](Week1/STA410_W24_Week1_CodingDemo_MemoryUsage.ipynb)
    3. [Homework: Modulus ](Week1/STA410_W24_Week1_Homework_ModulusRecursion.ipynb)[Recursion](https://www.google.com/search?q=recursion)
    4. [Extra Coding: New to `python`?](Week1/STA410_W24_Week1_NewToPython_IntegerBinaryRepresentation.ipynb)
    5. [Extra Reading: Pseudorandomnes and Floating-point numbers](Week1/STA410_W24_Week1_Extra_PseudorandomnesAndComputerRepresentation.ipynb)
2. Estimation: Monte Carlo (MC) integration, estimation error, improving efficiency, antithetic sampling and control variates (correlation) 
    1. [Lecture Notebook](Week2/STA410_W24_Week2_Lecture_Estimation.ipynb)
    2. [Coding Demo: Adaptive Squeezed Rejection Sampling](Week2/STA410_W24_Week2_Demo_AdaptiveRejectionSampling.ipynb)
    3. [Homework: Integration Estimation](Week2/STA410_W24_Week2_Homework_EstimationViaSampling.ipynb)
    4. [Extra Reading: Integral Approximation](Week2/STA410_W24_Week2_Extra_IntegralApproximation.ipynb)       
    5. [Extra Reading: Importance Sampling Bias](Week2/STA410_W24_Week2_Extra_ImportanceSamplingBias.ipynb)
    6. [Extra Coding: Importance Sampling Hidden Markov Models (HMMs)](Week2/STA410_W24_Week2_Extra_AdvancedPython_ImportanceSamplingHMMs.ipynb)
    7. [Extra Reading: HMMs](Week2/STA410_W24_Week2_Extra_XiaoxuanHan_HMM_LikelihoodStateInference_ForwardViterbiBaum-Welch.pptx)
3. Markov Chain Monte Carlo (MCMC): High dimensional integration, Gibbs Sampling, Slice Sampling, Metropolis-Hastings, `PyMC`, Hamiltonian Monte Carlo (HMC)
    1. [Lecture Notebook](Week3/STA410_W24_Week3_Lecture_HighDimentionalIntegration.ipynb)
    2. [Coding Demo: Hamiltonian Monte Carlo with PyMC](Week3/STA410_W24_Week3_Demo_HMCwithPyMC.ipynb)
    3. [Homework: Probabilistic Programming](Week3/STA410_W24_Week3_Homework_ProbabilisticProgrammingPyMC.ipynb)
    4. [Extra Coding: `PyMC` `python`](Week3/STA410_W24_Week3_Extra_PyMCPython_ProbabilisticProgramming.ipynb)
    5. [Extra Reading: MCMC Diagnostics and Theory](Week3/STA410_W24_Week3_Extra_MCMCdiagnosticsAndTheory.ipynb)
4. Numerical precision and error and condition and linear algebra (floating point behaviour and SVD)
    1. [Lecture Notebook](Week4/STA410_W24_Week4_Lecture_NumericalErrors.ipynb)
    2. No Coding Demo this week and we'll have a long lecture instead; the ***prerequesite*** reading becomes important for the end of this lecture and relevance continues into future material; what was being considered for the ***Coding Demo*** has instead just remained as part of the ***Homework*** [so the homework is a little longer in length than usual]
    3. [Prerequesites: Linear Algebra](Week4/STA410_W24_Week4_Prerequesite_LinearAlgebra.ipynb)
    4. [Homework: Numerical Precision for Means and Variances](Week4/STA410_W24_Week4_Homework_AdditionVariance.ipynb)
    5. [Extra Reading: Analog versus Digital Arithmatic](Week4/STA410_W24_Week4_Extra_AnalogVsDigital_BitstringArithmatic_GracefulUnderflow.ipynb)
5. Linear Algebra: SVD/PCA/ICA/PRC, Condition, Regression VIFs, and Matrix Decompositions for Least Squares
    1. [Prerequesites: Linear Algebra](Week4/STA410_W24_Week4_Prerequesite_LinearAlgebra.ipynb) **[Still (or now actually probably Even More) applicable compared to Last Week...]**
    2. [Lecture Notebook](Week5/STA410_W24_Week5_Lecture_UsingLinearAlgebra.ipynb)
    3. [Coding Demo: Least Squares](Week5/STA410_W24_Week5_Demo_LeastSquares.ipynb)
    4. [Homework: Randomized Linear Algebra](Week5/STA410_W24_Week5_Homework_RandomizedLinearAlgebra.ipynb)
    5. [Extra Coding: Gram-Schmidt and the Cholesky](Week5/STA410_W24_Week5_Extra_LinearAlgebraAlgorithms.ipynb)
    6. [Extra Coding: More Least Squares](Week5/STA410_W24_Week5_Extra_MoreLeastSquares.ipynb)
    7. [Extra Reading: Computational Speed and Complexity](Week5/STA410_W24_Week5_Extra_SpeedAndBigOAlgorithmicComplexity.ipynb)
    8. [Extra Reading: Matrix Condition Numbers](Week5/STA410_W24_Week5_Extra_DerivingMatrixCondition.ipynb)
6. Coding Challenge
7. Reading Week
8. Midterm
9. From (Week 5) ***Direct Methods*** to ***Iterative Methods***: Gauss-Seidel (GS), Successive Overrelaxation, Coordinate Descent (AKA Nonlinear GS), and Gradient Descent and AutoDiff
    1. [Coding Demo: Splines, smoothing matrices (lowess/loess), generalized additive models (GAMs)](Week6/STA410_W24_Week6_Demo_FunctionRepresentation.ipynb)<br>[including some extra broader contextual material on basis functions and regularization and penalty functions]
    2. [Lecture Notebook](Week6/STA410_W24_Week6_Lecture_IterativeMethods.ipynb) 
    3. [Homework: Gradient Descent](Week6/STA410_W24_Week6_Homework_GradientDescent.ipynb) 
    4. [Extra Reading: Line Search to find optimal step sizes and Conjugate Gradient Descent](Week6/STA410_W24_Week6_Extra_LineSearch_ConjugateGradientMethods.ipynb)
    5. [Extra Coding: Conjugate Gradient Descent](Week6/STA410_W24_Week6_Extra_ConjugateGradientDescent.ipynb)
    6. [Extra Reading: Function Spaces](Week6/STA410_W24_Week6_Extra_FunctionSpaces.ipynb)
    7. [Extra Coding: Lagrange Polynomial Interpolation](Week6/STA410_W24_Week6_Extra_LagrangePolynomialInterpolation.ipynb)
10. Optimization, Hessians and Jacobians, Gauss-Newton, Maximum Likelihood Estimation (score function, etc.) and Fisher Scoring and Newton's Method
    1. [Lecture Notebook](Week7/STA410_W24_Week7_Lecture_Optimization.ipynb)
    2. (+ iii) [Coding Demo / Homework Notebook: classical optimization methods in TensorFlow](Week7/STA410_W24_Week7_CodingDemo_and_Homework_Optimization.ipynb)<br>(with Nonlinear Gauss-Seidel, Gradient Descent, Gauss-Newton, Fisher Scoring, and Newton's Method)
    3. ^
    4. [Extra Reading: Variants on Newton's Method and Convergence Considerations](Week7/STA410_W24_Week7_Extra_NewtonVariantsConvergence.ipynb)
    5. [Extra Coding: Newton's Method versus Secant, Fixed-Point Iteration, etc.](Week7/STA410_W24_Week7_Extra_NewtonVsSecantVsFixedPointIteration.ipynb)
11. Newton's Method Sandwich Estimators and IRLS (iteratively reweighted keast squares) (including M and Quasi-Likelihood estimation)
    1. [Lecture Notebook](Week8/STA410_W24_Week8_Lecture_IRLS.ipynb)
    2. [STRONGLY Recommended Extra Reading: Modern Optimizers are Newton's Method simplificaitons](STA410_W24_Week8_STRONGLYRecommended_Optimizers.ipynb)
    3. [Homework: Logistic Regression via IRLS](Week8/STA410_W24_Week8_Homework_LogisticRegressionIRLS.ipynb)
    4. [Coding Demo: Gauss-Newton](Week8/STA410_W24_Week8_CodingDemo_GaussNewton.ipynb)
    5. [Extra Coding: Huber Loss](Week8/STA410_W24_Week8_Extra_HuberLossIRLS.ipynb)
12. Variational Inference, EM algorithm, Deep Learning (no Constrained optimization)
13. Coding Challenge
14. Final
