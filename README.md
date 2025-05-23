### EX2 Generating Association Rules for Employee dataset using Apriori Algorithm
### AIM: To generate associate rules for the employee dataset using Apriori Algorithm.
### Description:
In data mining, association rule learning is a popular and well researched method for discovering interesting
relations between variables in large databases. It can be described as analyzing and presenting strong rules discovered
in databases using different measures of interestingness. In market basket analysis association rules are used and they
are also employed in many application areas including Web usage mining, intrusion detection and bioinformatics.
Creation of Buying Table:
### Procedure:
1) Open Start -> Programs -> Accessories -> Notepad
2) Type the following training data set with the help of Notepad for Buying Table.

```
@relation buying
@attribute age {L20,20-40,G40}
@attribute income {high,medium,low}
@attribute stud {yes,no}
@attribute creditrate {fair,excellent}
@attribute buyscomp {yes,no}
@data
L20,high,no,fair,yes
20-40,low,yes,fair,yes
G40,medium,yes,fair,yes
L20,low,no,fair,no
G40,high,no,excellent,yes
L20,low,yes,fair,yes
20-40,high,yes,excellent,no
G40,low,no,fair,yes
L20,high,yes,excellent,yes
G40,high,no,fair,yes
L20,low,yes,excellent,no
G40,high,yes,excellent,no
20-40,medium,yes,excellent,yes
L20,medium,yes,fair,yes
G40,high,yes,excellent,yes
```
3) After that the file is saved with .arff file format.
4) Minimize the arff file and then open Start -> Programs -> weka-3-4.
5) Click on weka-3-4, then Weka dialog box is displayed on the screen.
6) In that dialog box there are four modes, click on explorer.
7) Explorer shows many options. In that click on ‘open file’ and select the arff file
8) Click on edit button which shows buying table on weka.
### OUTPUT:
# Buying
![buying](https://github.com/user-attachments/assets/5b28f04d-828d-48e0-8439-1ffbf7441454)
# Employee
![2employee](https://github.com/user-attachments/assets/27549214-3cf8-4237-bf46-342fd4753295)
# Bank
![bank](https://github.com/user-attachments/assets/8b572d14-0318-4e6a-b768-a2f98530c73e)

### Procedure for Association Rules:
1) Open Start -> Programs -> Accessories -> Notepad
2) Open explorer.
3) Click on open file and select buying.arff
4) Select Associate option on the top of the Menu bar.
5) Select Choose button and then click on Apriori Algorithm.
6) Click on Start button and output will be displayed on the right side of the window.

### OUTPUT:
# Buying
![buying2](https://github.com/user-attachments/assets/dabb6a55-8375-4d25-934f-351f60536fbf)
# Employee
![22employee](https://github.com/user-attachments/assets/fcf9bd6c-2d78-482e-a7cf-d5afddf2e0c9)
# Bank
![2bank](https://github.com/user-attachments/assets/eea5edd4-2c61-4080-b909-8390505e2de1)

### RESULT: 
Thus this program has been successfully executed.
