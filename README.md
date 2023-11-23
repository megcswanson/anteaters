# anteaters
USMR group project - aggregating anteaters group
Please make comments on any changes made to the RMarkdown file. 
If you have any questions about a change someone has made, please text in the group chat. 

Remember to push origin and pull when necessary. 
Check the changes made in Github before saving to your computer. 
Create a new branch if needed. 

# to do list: 
- plot and describe categorical variables
  - violin plots for each dependent variables (relation to the dependent variables)
- give a marginal distribution through a stacked bar plot - show the number of people in each emoji category using each opsys

For question 1: set categorical variables as factors; 
1a - t.test() independent sample (week 3)
1b - cor() (week 5)
1c - chisq() (week 4)

question 2
- model comparisons (week 8b)
- or 1 model anova (week 8)
- for model: use treatment contrasts on opsys (week 9) and for emoji category (week 9)
  - this uses the grand mean for comparison instead of apple or android 
- for EV, we need to standardize by SDs (standardize the outcome) such that we have a scale for interpretation so that we can say "this increases EV by one SD" instead of whatever unit the EV is currentlt presented in (week 8) like so: scale(data, center = FALSE)