# DA-project-1
ECON 5200 Midterm Project -- Track A: The Causal Policy Track (Difference-in-Differences)
Link to paper Card, D., & Krueger, A. B. (1994). "Minimum Wages and Employment: A Case Study of the Fast-Food Industry in New Jersey and Pennsylvania." https://davidcard.berkeley.edu/papers/njmin-aer.pdf


The primary question being investigated in this research is the effect an increase of the minimum wage had on employment for fast food workers. The data surveys fast food locations in the New Jersey/Pennsylvania border region -- NJ having recently raised its minimum wage at the time of this study, and Pennsylvania's wage remaining constant. 


**Event Study Extension of Card & Krueger (1994): Dynamic Employment Effects of the New Jersey Minimum Wage Increase**

This study extends Card & Krueger's (1994) seminal difference-in-differences analysis of the New Jersey minimum wage increase by applying an event study design using Bureau of Labor Statistics quarterly data on limited service restaurant employment from 1990 to 1994. While the original paper was limited to a single before and after comparison of 410 fast-food stores, this extension tests the parallel trends assumption formally and examines whether the employment effects of the minimum wage persisted and evolved dynamically over time. The pre-trend analysis finds a `time_to_treat:Treat` coefficient of virtually zero (`0.000086`, p = `0.986`), providing strong statistical confirmation that New Jersey and Pennsylvania were on identical employment trajectories in the eight quarters prior to the April 1992 minimum wage increase — validating the core identifying assumption of the original paper's design.

The post-treatment analysis reveals that the minimum wage increase produced no immediate employment shock (`Treat:Post` = `-0.029`, p = `0.349`), but instead generated a gradual and statistically significant divergence in employment growth between the two states. The `time_to_treat:Treat:Post` coefficient of `0.0125` (p = `0.032`) indicates that New Jersey's limited service restaurant employment grew approximately 1.3% per quarter faster than Pennsylvania's in the eleven quarters following the minimum wage increase, while Pennsylvania's own trend remained stable and unchanged throughout the post-treatment period. These findings not only corroborate Card & Krueger's conclusion that the minimum wage did not reduce employment, but extend it by demonstrating that the positive employment effect was gradual, persistent, and grew stronger over time — a dynamic pattern consistent with firms slowly adjusting hiring practices in response to the improved labor market conditions created by the higher minimum wage.

# Executive Memo


**Key Findings**
1. No evidence that minimum wage reduces employment
2. No immediate employment shock after the policy
3. ⁠NJ employment grew ~1.3% faster per quarter post-treatment
4. Strong support for parallel trends assumption

In replicating and then extending the Card & Krueger (1994) study, the following conclusions were identified. The replication produced the same results as the original paper, which were that an increase to the minimum wage for fast food workers in NJ saw a correlated increase in employment in the fast food sector; the extension broadened the study out to a 4 year window, which showed that employment trends were in fact parallel to Pennsylvania before the wage increase, and saw a gradual but significant increase following that change.

The mechanisim this study used was DID - Difference in difference. The researchers took advantage of a naturally occurring experiment, with Pennsylvania (control) maintaining the same wage level while simultaneously New Jersey (treated) increased their minimum wage level. The resulting statistical takeaways come from a comparison of these two groups, letting us view the economic trends that correspond to this one specific treatment. The extension continued in using DID paired with an event study to get a wider horizon with which to view each group's trend. Below is a visualization from the extension showing the groups' respective log wage trends with a smoothed rolling average for easy comparison:
<img width="1189" height="590" alt="image" src="https://github.com/user-attachments/assets/7d9bf123-c2da-42ee-a3df-3379b80a28cf" />

Based on the original paper's findings as well as the extension, the obvious policy action would be that wage increases have a strong effect on increasing employment. It remains unclear if this correlation would be applicable to other higher-skilled or specialized sectors, but for sectors comparable to fast food, employment struggles can be counteracted with higher wages for workers.
