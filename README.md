### Project Information
```
Project Title: "Credit Where Credit is Due: Mitigating racial unfairness in credit risk data with the Fairlearn toolkit"
By: Gia Musselwhite for Princeton University course SML 312
Paper submitted: 12/6/2024 / Presented on: 12/8/2024 / Code submitted: 12/12/2024
```
```
Project adapted for the Wooldridge 'loanapp' dataset using SML 312 precept code, Fairlearn example notebooks Credit Loan Decisions documentation (https://fairlearn.org/main/auto_examples/plot_credit_loan_decisions.html#footcite-dudik2020assessing), and other online tutorials
```

```
// Abstract: 
Are unfairness mitigation strategies, like threshold optimizer algorithms, able to reduce unfair outcomes in the field of credit scoring classification tasks? This paper builds on a 2024 project by Chunyu Yang, which found the white identity variable to be of high importance in mortgage applications approvals/rejections, and tests the Fairlearn unfairness mitigation toolkit for binary classification. In this paper, I first conduct exploratory data analysis, feature importance visualizations, and robust classification modelling on the 1996 Wooldridge ‘loanapp’ dataset. Afterwards, I attempt to mitigate unfairness due to racial identity in ‘loanapp’ decisions, following the Fairlearn Credit Loan Decisions documentation. I find that postprocessing techniques using threshold optimization reduce disparities between white and non-white applicants for both false positive and false negative credit approval rates. This successfully minimizes the equalizer odds difference and mitigates unfairness in lightgbm dataset classification.
```

```
References: 
Munkhdalai, L., Munkhdalai, T., Namsrai, O.-E., Lee, J. Y., & Ryu, K. H. (2019, January 29). An empirical comparison of machine-learning methods on bank client credit assessments. MDPI. https://www.mdpi.com/2071-1050/11/3/699.
Stelzer, A. (2019). Predicting credit default probabilities using machine learning techniques in the face of unequal class distributions. ArXiv, abs/1907.12996.
Hofmann, H. (1994). Statlog (German Credit Data) [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C5NC77.
South German Credit [Dataset]. (2020). UCI Machine Learning Repository. https://doi.org/10.24432/C5QG88.
GeeksforGeeks. (2024, May 15). How to visualize a decision tree from a random forest. https://www.geeksforgeeks.org/ways-to-visualize-individual-decision-trees-in-a-random-forest/ 
Mahadevan, M. (2024, November 22). Step-by-step exploratory data analysis (EDA) using Python. Analytics Vidhya. https://www.analyticsvidhya.com/blog/2022/07/step-by-step-exploratory-data-analysis-eda-using-python/ 
Predicting categorical data using classification algorithms - shiksha online. Shiksha Online. (n.d.). https://www.shiksha.com/online-courses/articles/predicting-categorical-data-using-classification-algorithms/ 
Grömping, U. (2019). South German Credit Data: Correcting a Widely Used Data Set. Berliner Hochschule Für Technik Reports in Mathematics, Physics and Chemistry. https://www1.beuth-hochschule.de/FB_II/reports/Report-2019-004.pdf.
ML: Extra tree classifier for feature selection. GeeksforGeeks. (2023, May 18). https://www.geeksforgeeks.org/ml-extra-tree-classifier-for-feature-selection/ 
Brownlee, J. (2020, June 3). Feature selection in python with scikit-learn. MachineLearningMastery.com. https://machinelearningmastery.com/feature-selection-in-python-with-scikit-learn/ 
Eight ways to perform feature selection with scikit-learn. Shedload Of Code. (2023, August 5). https://www.shedloadofcode.com/blog/eight-ways-to-perform-feature-selection-with-scikit-learn 
Feature importance. Feature importance - Scikit-learn course. (n.d.). https://inria.github.io/scikit-learn-mooc/python_scripts/dev_features_importance.html
Weerts, H., Dudík, M., Edgar, R., Jalali, A., Lutz, R., & Madaio, M. (2023, March 29). Fairlearn: Assessing and improving fairness of AI Systems. arXiv.org. https://arxiv.org/abs/2303.16626 
Dudík, M., Chen, W., Barocas, S., Inchiosa, M., Lewins, N., Oprescu, M., Qiao, J., Sameki, M., Schlener, M., Tuo, J., & Wallach, H. (2020). Assessing and mitigating unfairness in credit models with the fairlearn toolkit. https://www.microsoft.com/en-us/research/uploads/prod/2020/09/Fairlearn-EY_WhitePaper-2020-09-22.pdf 
Fairlearn. (n.d.). Credit loan decisions documentation (Example Notebooks). Microsoft. https://fairlearn.org/main/auto_examples/plot_credit_loan_decisions.html#footcite-dudik2020assessing 
Munnell, Alicia H, Geoffrey MB Tootell, Lynn E Browne, and James McEneaney, “Mortgage lending in Boston: Interpreting HMDA data,” The American Economic Review, 1996, pp. 25–53.
Martinez, E., & Kirchner, L. (2021, August 25). The secret bias hidden in mortgage-approval algorithms – the Markup. The Markup. https://themarkup.org/denied/2021/08/25/the-secret-bias-hidden-in-mortgage-approval-algorithms 
Małowiecki, A., & Chomiak-Orsa, I. (2024). Fairlearn parity constraints for mitigating gender bias in binary classification models – comparative analysis. Communications in Computer and Information Science, 148–154. https://doi.org/10.1007/978-3-031-50485-3_13 
Wooldridge, J.M. (2020). 115 Data Sets from "Introductory Econometrics: A Modern Approach, 7e.” rdrr.io. https://rdrr.io/cran/wooldridge/
Hunter, W.C. and Walker, M.B. (1996), “The Cultural Affinity Hypothesis and  Mortgage Lending Decisions,” Journal of Real Estate Finance and Economics 13, 57-70.
Wooldridge. PyPI. (n.d.). https://pypi.org/project/wooldridge/0.1.0/ 
Yang, C. (2024). Research on loan approval and credit risk based on the comparison of machine learning models. SHS Web of Conferences, 181, 02003. https://doi.org/10.1051/shsconf/202418102003 
Skowronski, J. (2017, April 14). All about the equal credit opportunity act. Human Rights Campaign. https://www.hrc.org/news/all-about-the-equal-credit-opportunity-act#:~:text=It%20was%20passed%20back%20in,Federal%20Reserve%20Bank%20of%20Philadelphia. 
```
