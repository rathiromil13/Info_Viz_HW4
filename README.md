## HW 4

## Solution 1

### Calculate and Visualize the proportion of each district’s total funding that will be lost.

Figure 1 below shows the proportion of each district's total funding that is lost.

![Proportion of Total Funding Lost](Figures/sol1.png)
###### Figure 1: Proportion of Total Funding Lost

Figure 2 shows the top 20 districts which are affected the most by the budget cuts.

![States most affected by funding cut](Figures/sol12.png)
###### Figure 2: 20 Districts affected most by budget cut 

## Solution 2

### Calculate and Visualize the proportion of each district’s total funding that will be lost.

Let's take a look at distribution of proportion of enrolled students by race for districts with budget cut as well as district without budget cut.

![Distribution of Proportion of Enrolled Students by Race](Figures/q2.png)
###### Figure 3: Distribution of Proportion of Enrolled Students by Race (Budget Cut vs Non Budget Cut)

Here, we can observe that for almost all the races, distribution is very similar. There is not much difference which can be observed from the quartile values in the violin plot above. The wider distribution of districts where budget cut is not performed shows that the less students were affected by the funding cut in case of all the communities. The upper adjacent values and lower adjacent values are almost similar. There is a minor shift for 'Blacks' and 'Hispanic' races in lower adjacent values from which we can conclude that there might be hidden bias for different communities but it's very less. Thus overall, it does a good job for majority of the people of different communities.

The Hawaiian and Pacific race is not completely visible so let's take a closer look to confirm the assumption that there is very small amount of hidden bias for different communities.


![Distribution of Proportion of Enrolled Students by Race](Figures/q21.png) 
###### Figure 4: Distribution of Proportion of Enrolled Students for Hawaiian or Pacific Race  (Budget Cut vs Non Budget Cut)


## Solution 3

### Calculate and Visualize the proportion of each district’s total funding that will be lost.

![Distribution of Proportion of Enrolled Disabled Students](Figures/q3.png)
###### Figure 5:Distribution of Proportion of Enrolled Disabled Students

From the figure above it can be observed that quartile values are adjacent to each other. Again, the distribution for districts where budget cut is false is wider, which shows that there is more chance that funding cut is not done for districts which has higher proportion of disable students.
Thus in case of disable students, again it shows there is not considerable hidden bias.


## Solution 4

For this problem, I chose to critique Tian Sang's HW3.  Link for the assignment : https://github.com/stiangithub/HW3

The method Tian suggested is very simple to understand and easy to implement - to cut 15% of the budget for each school district. Tian reasoned it would be not fair to cut the same amount from each school district which makes sense as the budget for schools are different and that might lead to creating a big deficit for schools with a small budget and hurt them in the long run as compared to other schools.

In my opinion there are certain important factors which Tian missed out on - cutting equal proportion from each district might result into increase debt for certain schools which have higher debt than the funding they were receiving which in turn will make them less competitive and give other schools an unfair edge over them. Therefore, the debt school has on their account should also be considered as it might hurt schools with high debt to cut 15% from their existing budget. 

Other factors that could be taken into account are the performance of schools as well as demographics of school to make sure the budget cut is completely from those schools where it'll not hurt the performance of the students so that they can get access to quality education by making sure schools with high debt receive enough funding so that they can sustain and remain competitive.


## Solution 5

For this problem, I would like to comment on Visualization Lecture. 

While I believe every lecture was informative, I found visualization one very useful as it explained why a powerful visualization is equally important skill set to have for a Data Scientist than any other skill. 

I believe often while focusing more on Data Processing and Modeling part, we miss out on creating impactful visualization by missing out on simple but subtle techniques. The lecture covered many things that makes a good visualization which we fail to notice as we are more focused on other aspects of the problem. It was refreshing to understand that everything is important in visualization, from choosing the type of visualization, the color scheme used for better interpretability, the size of plots and selection of shape and size of data points. I certainly believe it'll be very helpful in future as now we'll pay more attention to details of visualization and make our method as well as results more interpretable.
