# Portfolio
👋 Hi, I'm Ruilan (Helen) Zeng
Welcome to my portfolio! I'm a dual-degree candidate at UC Santa Barbara pursuing a B.S. in Financial Mathematics & Statistics and a B.A. in Economics & Accounting, with international experience at Sciences Po Paris and The University of Hong Kong. My interests lie at the intersection of quantitative finance, AI machine learning, and data-driven decision making.

Throughout my internships and academic journey, I’ve worked on projects ranging from real estate conversion and credit fund modeling to biological data analysis and market strategy consulting. While some of my most technically advanced work—particularly involving confidential real estate conversion models and investor materials—cannot be publicly shared, I've included a few public-facing projects below to showcase my analytical workflow and modeling style.

🔍 Featured Projects

**🧮 Cubic Spline Extrapolation Stress Test · Python**  
- Built NumPy/SciPy harness on 120+ random grids to probe edge behavior  
- Found natural splines flatten past domain; patched boundary logic; added unit tests

**₿ Next-Day Bitcoin Return Forecasting · R**  
- Ingested 1-min Bitstamp data to daily features, engineered lags and volumes  
- Benchmarked AR(1), OLS, Elastic Net, Random Forest with rolling TS CV; best RMSE ≈ 2.9% (barely beats mean)

**🎮 Pokémon Type Predictor · R (tidymodels)**  
- Dataset: 800+ Pokémon with 12 features (base stats, height, weight, generation, abilities)  
- Preprocessing: one-hot encode generation & abilities, center/scale stats, PCA to 30 components  
- Models & tuning:  
  - Multinomial GLMNET (α=0.5, λ tuned to 0.02) → 72 % accuracy  
  - Ranger RF (mtry=4, trees=500, min_n=5) → 85 % accuracy  
- Evaluation: RF recall 95 % on common types (Water, Normal), precision 60 % on rare types (Fairy, Steel); macro F1 ≈ 0.78  
- Next steps: apply SMOTE and class-weighted sampling to boost minority-type recall and reduce bias
 
**💎 Diamond Pricing Model Regression · Python**  
- Used multiple and log-transformed regression models to predict diamond prices based on carat, cut, depth, and color.
- Built and refined regression models with R² > 0.86
- Conducted Spearman correlation analysis and backward AIC-based feature selection
- Performed residual diagnostics and multicollinearity checks

**📊 Stochastic Simulation & Option Pricing · Python**  
- Simulated Brownian motion & Brownian bridge with a Karhunen–Loève expansion and custom eigenfunctions/eigenvalues. 
- Wrote Euler–Maruyama engines for GBM and CIR and matched Monte Carlo mean/variance to theory (CIR Var ≈ 0.0125) 
- Cross-checked analytics vs simulation: P(S₂<40) ≈ 0.961, Black–Scholes call ≈ $24.56, IV ≈ 46.9%. 

🛑 Note on Confidentiality
Some of my most impactful work—particularly those involving real estate acquisitions, private equity fundraising, and credit portfolio strategies—contains proprietary financial data and cannot be publicly posted. Please reach out if you’d like to discuss these experiences further in a one-on-one setting.

📬 Let’s Connect!
Feel free to connect with me on LinkedIn or reach out directly at rzeng@ucsb.edu. I’m always excited to collaborate on data-driven, impactful work in finance and strategy.
