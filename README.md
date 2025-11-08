Two Stata files in the working directory:

- `Tanzania_2012.dta`
- `Tanzania_2018.dta`

It computes the three Foster–Greer–Thorbecke (FGT) poverty measures (headcount P0, poverty gap P1, squared poverty gap P2) at:

- national level
- by stratum (STRATUM: rural, other urban, Dar es Salaam)
- by region

For **two poverty lines**: `povline` and `food_povline` contained in the datasets.

It uses household sampling weights (`hhweight`) and household size (`hhsize`) to compute *population (person-level) measures*.
