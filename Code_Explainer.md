📘 Code Explainer: Monte Carlo Financial Engine

This document translates the mathematical simulation code into universal language for non-technical stakeholders.

1. Modeling Financial Uncertainty

np.random.uniform(0.15, 0.54): Instead of using a single biased growth percentage guess, this tells the simulator that annual cloud hardware data center infrastructure spending could realistically range between a 15% floor and a 54% ceiling.
current_revenue_bn * ((1 + annual_growth_rate) ** 2): This uses compound growth math to calculate where NVIDIA's base revenue will land over a 2-year timeline under 2,000 distinct parallel realities.
base_net_margin - np.random.uniform(0.0, 0.08): This simulates real-world industry friction. We subtract up to 8% from corporate profit margins to represent competitors creating their own internal custom tensor processing silicon chips, forcing down prices.
2. Slicing Out Volatility

np.percentile(..., 10) & np.percentile(..., 90): Financial analysts use percentiles to manage risk. The 10th percentile calculates the "Bear Case" (what happens if all negative macro constraints hit at once), while the 90th percentile maps the "Bull Case" (maximum market upside).
