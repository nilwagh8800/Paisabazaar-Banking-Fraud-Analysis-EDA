![image alt](https://github.com/nilwagh8800/Paisabazaar-Banking-Fraud-Analysis-EDA/blob/2bd5a49cf5bec31733fe26f926d81dddc064a72a/logo.png)

# Banking-Fraud-Analysis-EDA
# Project Summary

In today’s financial landscape, accurate credit score assessment is vital for both financial institutions and customers. Paisabazaar, a financial services company, helps individuals find and apply for banking and credit products. A key aspect of their business involves assessing customers’ creditworthiness to provide personalized financial recommendations and ensure sound risk management practices. This case study focuses on analyzing, classifying, and predicting credit scores based on a range of customer data, such as income, credit card usage, and payment behavior. The goal is to help Paisabazaar improve their credit assessment processes, reduce loan defaults, and optimize customer services through better-informed decisions.

### Univariate Analysis

The first step in the analysis involves understanding the individual distributions of the features through univariate analysis. Age distribution is explored using a histogrt, providing insights into the primary demographic segments of the customer base. By examining the spread of ages, Paisabazaar can identify the dominant age group they cater to, which can inform targeted financial products for specific age brackets.

Income, another crucial feature, is analyzed by plotting histograms of both **Annual_Income** and **Monthly_Inhand_Salary**. Understanding the distribution of income among customers helps in evaluating the affordability of various loan products and identifying potential default risks. Customers with lower incomes might struggle with higher financial obligations, while high-income individuals may have better access to premium financial products.

The **Credit_Score**, the target variable, is visualized t hart or bar plot to showcase its distribution across three categories: Good, Standard, and Poor. This analysis helps in understanding whether the dataset is balanced or if it leans more toward a specific group, which can influence model performance. Class imbalance could lead to biased predictions, so this check is critical for fair modeling.

Credit utilization is a key factor in credit score determination, and a box plot is used to display the spread of **Credit_Utilization_Ratio**. This analysis highlights potential outliers and trends within the dataset, helping to assess whether certain customers are over-leveraged, which could increase their risk o

The interest rate represents the cost of borrowing for the customer, and it is crucial to understand how these rates are distributed across the customer base. A histogram is used to visualize the spread of interest rates. This gives insight into the range of interest rates being charged and helps identify trends such as whether most customers are paying lower or higher rates.f default.

### Bivariate Analysis

To delve deeper into the relationships between features and the target variable, bivariate analysis is performed. For instance, by comparing **Credit_Score** against **Age** using a box plot, the analysis seeks to determine if older individuals tend to have better credit scores, as they might have longer credit histories and more stable financial conditions.

Similarly, a bivariate analysis of **Annual_Income** and **Monthly_Inhand_Salary** against **Credit_g a box plot or violin plot reveals potential income disparities across the credit score categories. Higher-income individuals are expected to have better credit scores, as they can handle their financial obligations more easily.

Another interesting comparison is betweeBank_Acc **Number_of_Loans** and **BoxS**. A stacked bar plot is employed to examine whether individuals with a greater number of loans tend to have lower scores, indicating a higher likelihood of overextending themselves financially. Such insights are important for developing better loan offerings and risk management strategies.

The relationship between **Delay_from_due_date** and **Credit_Score** is also explored ter plot or box plot. This analysis helps reveal whether longer delays in payment correlate with lower credit scores, providing a clear indication of how payment punctuality impac

We also analyzed the impact of **designation** on **Credit Score** in relation to **Credit_Score** and **Occupation**. This helps reveal how individuals with different job positions or designations are distributed across various credit score categories. A bar chart was used to illustrate which occupations are more likely to have good, standard, or poor credit scores.
s financial health.

### Multivariate Analysis

Multivariate analysis builds upon the insights gathered from the univariate and bivariate analyses, offering a more comprehensive understanding of how multiple features interact with one another and the target variable. A pair plot is generated to visualize relationships between key variables, such as **Annual_Income**, **Outstanding_Debt**, **Credit_Utilization_Ratio**, and **Credit_History_Age**, alongside the **Credit_Score**. This allows for the identification of significant trends and relationships across multiple features simultaneously.

A correlation heatmap is also created, displaying the relationships between numerical variables like **Num_Credit_Card**, **Credit_Utilization_Ratio**, and **Outstanding_Debt**. Strong correlations between certain features can help in selecting the most important variables for building the crediction and financial performance.

# Problem Statement
Paisabazaar, a leading financial services company, relies on accurate assessment of customer creditworthiness to facilitate loan approvals and mitigate financial risks. A crucial component of this assessment is the classification of credit scores, which helps determine an individual’s likelihood to repay loans or manage credit balances. Current methods of credit score evaluation can be further enhanced through advanced data analysis and modeling.

This case study aims to address the challenge of accurately predicting credit scores based on customer data, including factors such as income, credit card usage, and payment behavior. The objective is to develop a predictive model that can assist Paisabazaar in improving credit assessment, reducing the risk of loan defaults, and providing personalized financial product recommendations, ultimately leading to better decision-making and customer satisfaction.


Business Objective


The primary business objective is to improve Paisabazaar's credit assessment process by accurately predicting individual credit scores based on customer data. By leveraging features such as income, credit card usage, loan history, and payment behavior, the goal is to:

1. **Enhance Credit Risk Management**: Improve the accuracy of credit score classification to better assess the creditworthiness of customers, minimizing the risk of loan defaults and bad debt.

2. **Personalize Financial Product Recommendations**: Use the predicted credit scores to offer tailored financial products, such as loans, credit cards, and insurance, based on individual financial profiles.

3. **Optimize Loan Approval Processes**: Streamline the loan approval system by automating credit score predictions, enabling faster and more efficient decisions.

4. **Increase Customer Satisfaction**: Provide customers with personalized financial advice and product recommendations, improving customer engagement and trust in Paisabazaar’s l offerings.

# Solution to Business Objective
suggest the client to achieve Business Objective

I suggest the client implement a predictive credit scoring model. This model can accurately predict individual credit scores based on customer data, enabling Paisabazaar to achieve its business objectives of:

Enhancing Credit Risk Management: By accurately assessing creditworthiness, the model can help minimize the risk of loan defaults and bad debt.

Personalizing Financial Product Recommendations: Tailored financial product offerings based on predicted credit scores can improve customer satisfaction and engagement.

Optimizing Loan Approval Processes: Automated credit score predictions can streamline the loan approval process, leading to faster and more efficient decisions.

Increasing Customer Satisfaction: Providing personalized financial advice and product recommendations can enhance customer trust and loyalty.
The model can be built using machine learning techniques, leveraging features such as income, credit card usage, loan history, and payment behavior to predict credit scores with high accuracy.

# Conclusion

The analysis of customer data provides valuable insights into the factors influencing credit scores and offers guidance for Paisabazaar's credit assessment processes. Key findings include a focus on the working population aged 25-45, a significant portion of customers with moderate to high earning capacity, a balanced credit score distribution with a notable portion having poor credit scores, responsible credit management among customers, a competitive market with varying interest rates, and the importance of age, income, credit utilization, and payment history in influencing credit scores. These findings offer valuable insights for Paisabazaar to refine their credit assessment models and improve risk management strategies by focusing on specific customer segments and tailoring their financial product offerings. Additionally, the analysis highlights the need for continuous monitoring of credit score trends and customer behavior to stay updated with evolving financial landscapes.


