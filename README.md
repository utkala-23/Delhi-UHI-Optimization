
Delhi Urban Heat Island (UHI) Optimization


AI-Driven Climate Mitigation using Reinforcement Learning
This project leverages Reinforcement Learning (PPO) and Satellite Data to architect optimal cooling strategies for New Delhi's most intense heat islands. By balancing budget constraints against thermal physics, the agent identifies where to plant trees, create parks, or apply reflective coatings for maximum impact.

Key Case Studies
1. The Concrete Jungle (IGIA Airport - Cell 317)Problem: High-intensity heat zone (41.03°C) with restricted space for vegetation.AI Strategy: Prioritized 50% Reflective Surfaces and 40% Green Roofs.Result: Achieved a 3.81°C cooling delta, successfully lowering the local LST below the 40°C danger threshold.
2. Nature-Based Efficiency (Aravalli Park - Cell 303)Problem: Maximizing existing ecological corridors.AI Strategy: Focused on high-density tree canopy expansion.Result: Validated as the most cost-efficient "Green Lung" in the NCR region.
3.  Model Performance & EconomicsSurrogate Model Accuracy: High-fidelity thermal prediction with an $R^2$ of 0.96 and MAE < 0.5°C.
4. Cost-Efficiency Frontier: The agent favored Tree Planting (Mean CEI: 7.1°C / ₹1M) for scalable cooling, while reserving Park Creation for high-priority hotspots.

Tech Stack


Agent: Stable Baselines3 (Proximal Policy Optimization - PPO)

Surrogate: Scikit-Learn Random Forest Regressor

Analysis: Pandas, NumPy, Matplotlib

Geospatial: Folium (Interactive Satellite Mapping) & Felt
