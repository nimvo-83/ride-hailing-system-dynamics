# Chicago’s ride-hailing market

When more drivers join a ride-hailing platform, passengers may find a ride more easily. But if the number of trips grows slowly, each driver gets a smaller share of the work. For my system dynamics project at the University of Tehran, I wanted to see how those two effects play out over time.

I built a stock-and-flow model in Vensim using monthly Chicago data from July 2022 to December 2025. The model connects drivers’ decisions to join or leave the platform with trip demand, fares and earnings. I compared the base run with historical data, then tested two policies under a rise in unemployment and a temporary increase in operating costs.

## What I found

Cutting the platform commission attracted more drivers. By December 2025, the simulation had about 57,700 active drivers, up from 52,100 in the base run, even though total trips were 2.6% lower. The $15 minimum fare had a different effect. It supported earnings during months when fares dipped, with less than a 1% difference in the final driver count.

The model smoothed out some of the swings in Chicago’s actual fares and demand. I used it to compare how the market responded to each policy over time.

## Exploring the project

- Read the [report](report.pdf) for the data sources, model assumptions and validation tests.
- Open the [causal loop diagram](models/CLD.mdl) in Vensim to trace the feedback loops, then run the [base model](models/SFD.mdl).
- The [policy results workbook](policy-results.xlsx) contains the monthly comparisons. The corresponding [Vensim models](models/) are grouped by policy and scenario.
