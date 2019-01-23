# A/B Test: E Commerce
For this project, I will be working to understand the results of an A/B test run by an e-commerce website if they should implement the new page, keep the old page, or perhaps run the experiment longer to make their decision.   

This project includes the following contents:
* Introduction
* Part I: Probability
* Part II: A/B test
* Part III: Regression
* Conclusion

Before Part I: Probability, I will perform data cleaning such as checking missing data, discrepancies between the columns etc.

### Language and Package
This project is using Python3. The packages are used in this project including Numpy, Panda, random, matplotlib.pyplot, scipy.stats, and  statsmodels.api.

### Metadata of variables
1. [ab_data.csv](https://github.com/jemc36/Udacity-DAND-AB-test-ecommerce/blob/master/ab_data.csv)  

| Variable Name | Metadata                   |
|---------------|----------------------------|
| user_id       | 6-digit numbers            |
| timestamp     | string                     |
| group         | string: control, treatment |
| landing_page  | string: old_page, new_page |
| converted     | numeric: 0:No, 1:Yes       |

2. [countries.csv](https://github.com/jemc36/Udacity-DAND-AB-test-ecommerce/blob/master/countries.csv)  

| Variable Name | Metadata           |
|---------------|--------------------|
| user_id       | 6-digit numbers    |
| country       | string: US, CA, UK |

### Methodology
* A/B Test
* Two-Proportion z Test
* Logistic Regression

### Report
The reports are generated to three formats, .ipynb, .pdf and .html:
* [Analyze_ab_test_results_notebook_jc.ipynb](https://github.com/jemc36/Udacity-DAND-AB-test-ecommerce/blob/master/Analyze_ab_test_results_notebook_jc.ipynb)
* [Analyze_ab_test_results_notebook_jc.pdf](https://github.com/jemc36/Udacity-DAND-AB-test-ecommerce/blob/master/Analyze_ab_test_results_notebook_jc.pdf)
* [Analyze_ab_test_results_notebook_jc.html](https://github.com/jemc36/Udacity-DAND-AB-test-ecommerce/blob/master/Analyze_ab_test_results_notebook_jc.html)

### Feedback from the reviewer
* [Udacity Reviews](https://github.com/jemc36/Udacity-DAND-AB-test-ecommerce/blob/master/Udacity%20Reviews.pdf)
