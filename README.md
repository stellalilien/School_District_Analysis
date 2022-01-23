# School District Analysis

## Overview
### Purpose of Updated Analysis

At the conclusion of the initial school district analysis we were informed of academic dishonesty regarding the Thomas High School 9th grade math and reading scores. In order to maintain the intergrity of the analysis it was requested that we replace all math and reading scores of the students in question with NaNs so they do not skew the overall passing percentages rankings in the district. Once these scores were replaced the initial analysis was repeated with the new totals.

## Results

### District Summary
Once the questionable student scores were replaced and the District Summary was recreated there were some slight changes: Average Math Score dropped from 79.0 to 78.9, % Passing Math dropped from 75.0 to 74.8, % Passing Reading dropped from 85.8 to 85.7, and the % Overall Passing dropped from 65.2 to 64.9.

#### Initial District Summary
<img width="296" alt="image" src="https://user-images.githubusercontent.com/94754972/150696523-3cb245d8-0886-4da5-9296-7193def41207.png">

#### Updated District Summary
<img width="295" alt="image" src="https://user-images.githubusercontent.com/94754972/150696565-ee85e192-6d8e-497c-8b9d-98526f5e9875.png">

### School Summary
In the school summary Thomas High School's data changed as follows: Average Math Score fell from 83.418349 to 83.350937, Average Reading Score rose slightly to 83.896082 from 83.848930, % Passing Math fell from 93.272171 to 93.185690, % Passing Reading fell from 97.308869 to 97.018739, and % Overall Passing fell from 90.948012 to 90.630324.

#### Initial School Summary
<img width="483" alt="image" src="https://user-images.githubusercontent.com/94754972/150696904-1ab98125-4fdf-4f1a-9b4f-07dae7be0c97.png">

#### Updated School Summary
<img width="349" alt="image" src="https://user-images.githubusercontent.com/94754972/150696927-965175d5-1a49-4f3d-9f88-3a40d3a9fef6.png">

### School Rankings
The updated data did not change the overall school rankings by passing percentage.

#### Initial School Rankings
<img width="381" alt="image" src="https://user-images.githubusercontent.com/94754972/150697305-ca36c52b-7cb3-437c-8821-3f36b1612740.png">

#### Updated School Rankings
<img width="351" alt="image" src="https://user-images.githubusercontent.com/94754972/150697322-064ae28d-a455-41a6-a3dc-767cf9c75594.png">

### Scores By Grade
The direct effect of removing the math and reading scores of Thomas High School 9th graders was that the passing percentage by grade was replaced by NaN in that category, all other percentages remained the same.
#### Initial Math Scores by Grade
<img width="156" alt="image" src="https://user-images.githubusercontent.com/94754972/150697610-7db5554b-0a9c-4798-9770-9f47fb5c32fd.png">

#### Updated Math Scores by Grade
<img width="157" alt="image" src="https://user-images.githubusercontent.com/94754972/150697636-4c395cb5-e4e8-4d3c-a2c6-8dc135a33b48.png">

#### Initial Reading Scores by Grade
<img width="155" alt="image" src="https://user-images.githubusercontent.com/94754972/150697654-88339e22-790f-4d6e-b2e6-59804549156f.png">

#### Updated Reading Scores by Grade
<img width="156" alt="image" src="https://user-images.githubusercontent.com/94754972/150697672-fdafe633-0bd8-4cef-a330-a15fce314c9c.png">

### Scores by Spending, Size, and Type
Removing the THS 9th grade scores did not have significant effects on the scores by spending, size, or type (when totals are formatted to the requested significant digits). 

## Summary

In conclusion, replacing the questionable scores lowered the Average Math Scores, % Passing Math, % Passing Reading, and % Overall Passing on the District level and it also lowered the same four categories on the school level. 
