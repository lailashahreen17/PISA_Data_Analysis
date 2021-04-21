# PISA Data Exploration

## Dataset

The PISA 2012 dataset is consisted of scores in math,reading and science and many other attributes of 485490 students. Total columns are 636. In order to explore our area of interest, the dataset is minimized to 124974 data points after preliminary wrangling and excluding missing values. The attributes are scores in three subjects along with  Country, Gender, Formative Assesment, Teacher Support, Teacher Student Relations,Socio_economic_cultural Status,Learning Time and Outside School Study Time.Dataset is availabale[here](https://www.google.com/url?q=https://s3.amazonaws.com/udacity-hosted-downloads/ud507/pisa2012.csv.zip&sa=D&ust=1554482573645000)


## Summary of Findings

In the exploration, I found that there was a moderate relationship between the
score of a student and his/her socio_economic_cultural status.When I compared the amount of time a student puts into their studies and the score they achieved, it ended up being practically no relationship between the Learning Time in each subject and  total Out-of-School Study Time/week , and each of the Score metrics. Although I digged deeper into the variables in later section, but they proved to be same with my earlier findings.

I tried to explore systematically and started with univariate exploration followed by bivariate and multivariate exploration. In univariate exploration, most of the variables showed normal distribution and I performed log transformation whenever needed.

Teachers' practices and attitude  have negetive co-relation coefficients with with scores. Collectively they are supposed to contribute to improve score but here the picture is opposite.

As for the section question of whether there are differences in achievement based on gender, the plot count and bivariate exploration revealed that it has not so much of impact on achievement. Location played a big role and we found out that East asian countries along with some European contries were top scorer.


## Key Insights for Presentation

For the presentation, I focused on just the influence of the location, gender, teachers' attitude and practices, students' study time outside school and learning effort  along with socio economic status affect the performance of students leave out most of the intermediate derivations. I started by introducing the average scores(math,science and reading) variables, followed by the pattern in location, gender, teachers' attitude and practices, students' study time outside school and learning effort distribution. Next came the pairplot of all my intended variables.

To answer my questions(mentioned at the top section of exploratory analaysis) in brief,

* Are there differences in achievement based on teacher practices and attitudes?

From bivariate exploration, it is more confirmed that there is not so strong relationship among teachers' attitude and practices with score. Countries those performed lower score had better help from teachers compared to high scoring countries.

Learning time and outside school study hours also do not show any strength in regard to average score.

* Are there differences in achievement based on gender, location, or student attitudes?
Yes location is important feature although the average scores in math, science and reading somehow lie within similar range but top scorer comes from particular regions.east asian countries are showing dominance. China is all along maintainting the highest average score. Japan is at second place for science and reading score where as Singapore is third. Singapore has second highes average math score.

Among the top ten countries, Germany, Taiwan, Korea, Belgium, Finland, Greece, Poland, Netherlands, Switzerland,Liechtenstein, Ireland are also present.

Indonesia, Peu, Qatar, Brazil and Argentina reamins in the worst five list.

Male and female students do not show that much variance in terms of scoring.

* Does socio-economic status matter?
The heat map below somehow can reflect the scenario of socio_economic_cultural status of different countries. Even though the high scorers in reading are withing small fraction of total students, but they are from better socio_economic status irrespective of country.
