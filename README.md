# Project 1: Standardized Test Analysis


### Overview

The SAT and ACT are standardized tests taken by high school students that are traditionally used by colleges and universities in their selection of new students.
There has been controversy over whether these tests are fair and accurate predictors of student success, and some universities have recently dropped requirements for applicants to participate in them.
The College Board and ACT, Inc. have been campaigning to maintain their role in the college  admissions process.



### Problem Statement

I’ll be taking the perspective of a state board of education, we are considering partnering with the SAT or ACT to increase participation in college entrance exams.  The purpose of this presentation is to determine whether to make one of these exams mandatory for high school graduation, and, if so, should it be the SAT or ACT



### Brief Summary of Analysis

- Import and cleaning of the following data
######
     * [`act_2017.csv`](./data/act_2017.csv): 2017 ACT Scores by State
     * [`act_2018.csv`](./data/act_2018.csv): 2018 ACT Scores by State
     * [`act_2019.csv`](./data/act_2019.csv): 2019 ACT Scores by State
     * [`sat_2017.csv`](./data/sat_2017.csv): 2017 SAT Scores by State
     * [`sat_2018.csv`](./data/sat_2018.csv): 2018 SAT Scores by State
     * [`sat_2019.csv`](./data/sat_2019.csv): 2019 SAT Scores by State
     * [`sat_2019.csv`](./data/sat_2019.csv): 2019 SAT Scores by State
     * [`bach_degree_25-34_2018`](./data/act_2017.xlsx): Population(Age 25-34) with Bachelor's or higher by state
     * [`college_bound_rates_2018`](./data/act_2017.xlsx): % of HS Grads going directly to college by state
 
- Exploratory data analysis of national trends in state participation in college-entrance exams  
- Investigation into correlations between SAT/ACT participation and higher education pursuit/attainment  
- Outside research into incentives to mandate statewide administration of SAT or ACT  
- Conclusions/Recommendations

### Data Dictionary

|Feature|Type|Dataset|Description|
|---|---|---|---|
|state|object|all_dfs|State|
|sat_part_17|float|all_dfs / testpart_college|2017 SAT participation rate|
|sat_total_17|int|all_dfs|2017 average SAT total score|
|sat_part_18|float|all_dfs / testpart_college|2018 SAT participation rate|
|sat_total_18|int|all_dfs|2018 average SAT total score|
|sat_part_19|float|all_dfs / testpart_college|2019 SAT participation rate|
|sat_total_19|int|all_dfs|2019 average SAT total score|
|act_part_17|float|all_dfs / testpart_college|2017 ACT participation rate|
|act_comp_17|float|all_dfs|2017 average ACT composite score|
|act_part_18|float|all_dfs / testpart_college|2018 ACT participation rate|
|act_comp_18|float|all_dfs|2018 average ACT composite score|
|act_part_19|float|all_dfs / testpart_college|2019 ACT participation rate|
|act_comp_19|float|all_dfs|2019 average ACT composite score|
|perc_college_bound|float|all_dfs|Estimated rate of high school graduates going directly to college in 2018|
|total_hs_grads|int|all_dfs|2018 Projected number of students graduating high school in 2018|
|tot_college_bound|int|all_dfs|Projected number of high school graduates going directly to college in 2018|
|perc_bach|float|all_dfs|Estimated percentage of the population age 25-34 with Bachelor's degree or higher in 2018|
|pop_bach|float|all_dfs|Estimated number of people age 25-34 with Bachelor's degree or higher in 2018|



### Conclusion

I recommend the state partner with the College Board to make the SAT mandatory for all high school graduates. Having a contract to administer the SAT will make college-entrance testing more accessible for all students, and will eliminate the need for the state to administer its own benchmark tests. While the ACT has had a higher number of states mandating the ACT in recent years, recent trends have shown a shift towards the SAT, and we should choose the same.  Since its redesign in 2016, the SAT is more closely aligned with state education benchmarks and is able to provide more resources for testing and preparation. Also, while participation in these tests did not show to be a strong predictor of with future success, SAT participation did show a slight correlation with attainment of higher education.  Along with forming a partnership with the College Board, it is recommended that the state work with local school districts to provide resources and testing days for students.  It is also recommended that further research be conducted to follow long-term trends between college-entrance exam participation and student success.

