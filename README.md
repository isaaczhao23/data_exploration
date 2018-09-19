# Correlation matrix
Arguments: 
- cor.method      Change correlation method. Can be "spearman" or "pearson". Default cor.method="spearman"
- size            Change size of text. Default size=1
- log.transform   Choose to make all numeric columns log transformed. Can be TRUE or FALSE. Default log.transform=FALSE.
- group           Choose to color scatterplot by a categorical variable. Put categorical variable name inside quotes. Defalt group=NULL

## Example:
custom_cormatrix(iris, cor.method="spearman", size=0.5, log.transform=FALSE, group ="Species")
![screen shot 2018-09-18 at 10 53 29 pm](https://user-images.githubusercontent.com/30127730/45728375-c128d500-bb95-11e8-8039-8890101159b9.png)
