# Data Fluency - Integrating Data and Expertise

In an ideal world, you have the experience and expertise to understand how every single piece of data was collected for use by your team. However, you often are in situations where you must rely on the knowledge of others to help you understand the data and how to best draw insights from it.

## The importance of Subject Matter Experts

Subject matter experts (SMEs) are individuals who have a deep understanding of a specific subject or area of expertise. They can provide valuable insights and information that can help organizations make informed decisions when working with data.

There are several reasons why SMEs are important when working with data:

  - Expertise: SMEs have extensive knowledge about a particular subject, which can be very useful when working with data related to that subject. They can provide valuable context and perspective that can help organizations better understand the data and make more informed decisions.
  - Accuracy: SMEs can help ensure the accuracy and reliability of data by reviewing and verifying it for errors or inconsistencies. This is especially important when working with data that will be used to make critical decisions.
  - Data interpretation: SMEs can help interpret data and provide insights that may not be immediately obvious to those who do not have a deep understanding of the subject matter. They can provide valuable insights that can help organizations make better informed decisions.
  - Communication: SMEs can help bridge the gap between data analysts and decision-makers by communicating complex data concepts in a way that is easier for non-experts to understand. This can help ensure that data is effectively used and that decisions are made based on accurate and reliable information.

Subject matter experts play a crucial role in helping organizations make informed decisions when working with data. They provide valuable expertise, accuracy, interpretation, and communication that can help organizations make the most of their data.

SMEs can also help us identify issues in your data analysis that should be addressed. This includes bias in both how the data was collected and also how it was analyzed.

## Bias in data analysis

Bias can play a significant role in data analysis, as it can influence the way that data is collected, the way that it is analyzed, and the way that conclusions are drawn from it. Bias can come in many forms, including cognitive and sampling bias. Cognitive bias is the result of mental shortcuts or preconceived notions that can influence how you interpret and analyze data. Sampling bias occurs when the sample of data that is collected is not representative of the entire population. It is important to be aware of the potential for bias in data analysis, and to take steps to minimize it, in order to ensure that the conclusions drawn from the data are accurate and reliable.

There are many ways in which bias can occur in predictive analytics. Some examples include:

  - Sampling bias: This occurs when the data used to train the predictive model is not representative of the entire population. For example, if the data used to train a model to predict creditworthiness is mostly from high-income individuals, the model may be less accurate for low-income individuals.
  - Selection bias: This occurs when the data used to train the predictive model is not chosen randomly, but is instead selected based on certain criteria. For example, if a model is trained on data from only a particular geographic region, it may not be representative of the entire population.
  - Confirmation bias: This is the tendency to search for, interpret, and prioritize information that confirms one's preconceptions or hypotheses. This can lead to overfitting, where the model performs well on the training data but poorly on unseen data.
  - Algorithmic bias: This occurs when the algorithms used to build the predictive model reflect the biases of the developers or the data used to train the model. For example, if a model is trained on data that includes more examples of one group than another, it may be biased against the underrepresented group.

It is important to be aware of these potential sources of bias and to take steps to minimize them in order to ensure that the predictive models are fair and accurate.

![Bias types](https://user-images.githubusercontent.com/12752033/210634207-c6bd1af6-e4df-4d04-b415-053f81d5e24a.png)

## Common data problems

There are many common problems that can arise when working with data. Some of the most common problems include:

  - Lack of quality: The data may be inaccurate, incomplete, or unreliable, which can lead to incorrect or misleading results.
  - Inconsistency: The data may be formatted or structured differently in different sources or at different times, which can make it difficult to combine or analyze.
  - Duplication: There may be multiple copies of the same data in different places, or the data may be repeated within the same dataset, which can inflate results or cause confusion.
  - Inability to access data: The data may be stored in a proprietary format or may be located in a hard-to-access location, which can make it difficult or impossible to use.
  - Large volume of data: The data may be too large or complex to be processed efficiently using traditional methods, requiring specialized tools and techniques to handle.
  - Sensitive data: The data may contain sensitive information that must be protected, such as personal or confidential information, which can create legal or ethical issues.
  - Outdated data: The data may be out of date, which can lead to incorrect conclusions or decisions if not properly accounted for.
  - Incorrect data types: The data may be stored in the wrong data type, such as a text field that should contain numeric values, which can prevent proper analysis or lead to incorrect results.
  - Lack of context: The data may not be accompanied by enough context or metadata to understand its meaning or significance, making it difficult to interpret or use effectively.
  - Incorrect assumptions: The data may be analyzed or interpreted based on incorrect assumptions, leading to incorrect conclusions or decisions.

To address these problems, it is important to carefully plan and execute the data collection process, ensure the data is cleaned and preprocessed appropriately, and use appropriate tools and techniques for analysis and visualization. It is also important to continually monitor and assess the quality and relevance of the data, and to be aware of any potential ethical or legal issues that may arise.

### Missing data

One of the most common data problems is missing data. There is no clear example of how to deal with every single type of missing data. It really depends on the data and the specific problem at hand in how missing data should be handled.

Missing data refers to data that are not available for a particular observation in a dataset. There can be several reasons for data to be missing, such as the data being lost, the participant in a study forgetting to provide an answer, or the participant choosing not to disclose certain information. There are several ways to deal with missing data, including:

  - Deletion: This involves deleting the entire row or column that contains missing data. However, this method is not recommended as it can result in a loss of a large amount of data, which can affect the validity of the results.
  - Imputation: This involves replacing the missing data with some estimated or imputed value. There are several methods of imputation, such as mean imputation, median imputation, and multiple imputation. Multiple imputation involves imputing multiple values for the missing data and then analyzing the data multiple times, taking into account the uncertainty introduced by the imputation process. The results are then combined to produce the final results.
  - Maximum likelihood estimation: This method involves estimating the missing data using the maximum likelihood function, which is the probability of the observed data given the missing data.
  - Expectation-maximization algorithm: This method involves iteratively estimating the missing data and the parameters of the model until the values converge.
  
It is important to carefully consider the best method to use for dealing with missing data, as the choice of method can significantly affect the results of the analysis.

### Working with imperfect data

So you have data that is likely not perfect. These are some strategies for working with imperfections.

Make sure to allot enough time for your data request to allow for documentation time. This can often be done by factoring in a cool down period after the initial work sprint where the data is documented and each column is analyzed further to check for outliers or changes in patterns over time. The focus here can be on explaining why choices were made. 

Just like your teachers asked you to show your work, it’s equally as important to keep your middle steps around. You may want to use something like an archive folder and processes for bigger projects. When you come back to look things over later, the hope is that you can backtrack and understand why you made the choices that you did. This allows you and your team to work more quickly on related projects and not need to reinvent the wheel over and over again.

Whenever possible, ensure that the process for collecting data is documented and a system is in place. Say there was an error in a particular column of your data, can you track down easily where that error occurred?

To reduce the errors in collected data, it’s often needed to just simplify the process. One example to often see this is with open-ended surveys. Suppose you were interested in following up with alumni at a school to better understand what pieces of the curriculum they use most in their day-to-day on the job based on which metropolitan area they live in. If you asked alumni what city they lived in, you might get responses like San Fran or Philly. These aren’t that difficult to map to the actual US city names, but the question itself could be simplified to provide options for the survey taker and a spot for them to clarify as needed. Then extra work won’t be needed except in the special cases of clarification.

It’s often hard to know if there are actually errors in data when it’s been handed to you without further context and historical information. If you yourself aren’t a SME, it is highly recommended you find who knows the most about the data you are working with so that further information can be given.

## Assessment/learning check questions

After reading the content above, take approximately 30 minutes to think about and note your responses to the questions below:

1. How do you and/or your team(s) identify problems in your data?
2. Do you have examples of issues with data you’ve seen in the past using your subject matter expertise? How were you able to resolve them? Who else helped you?
3. What steps can you take to detect data problems automatically?

