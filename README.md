# ESOC2024
ESOC Poster presentation

#### Abstract N°: 2716
#### Track: STUDIES
#### Category: 4.06 EPIDEMIOLOGY & RISK FACTORS
## Title: RAINSTORMS WITH A SPLASH OF BLOOD: MACHINE LEARNING-BASED PREDICTIVE ANALYTICS FOR HEMORRHAGIC STROKE ADMISSION BASED ON WEATHER SYSTEMS
$Mate Maros^1$, $Nandhini Santhanam^2$, $Stefan Muthers^3$, $Andreas Bender^4$, $David Ruegamer^4$,
$Franz-Simon Centner^5$, $Wenz Holger^6$, $Michael Neumaier^7$, $Fabian Siegel^2$


1Medical Faculty Mannheim, Heidelberg University, Departments of Neuroradiology & Biomedical
Informatics (DBMI), Mannheim, Germany, 2Medical Faculty Mannheim, Heidelberg University,
Department of Biomedical Informatics (DBMI), Mannheim, Germany, 3German Weather Service
(DWD), Research Centre Human Biometeorology (ZMMF), Freiburg, Germany, 4Ludwig Maximilian
University of Munich, The Statistical Consulting Unit (StaBLab), Department of Statistics, München,
Germany, 5Medical Faculty Mannheim, Heidelberg University, Department of Anesthesiology and
Surgical Intensive Care Medicine, Mannheim, Germany, 6Medical Faculty Mannheim, Heidelberg
University, Department of Neuroradiology, Mannheim, Germany, 7Medical Faculty Mannheim,
Heidelberg University, Institute of Clinical Chemistry, Mannheim, Germany

#### Background and aims: 
The climate crisis impacts cardiovascular health and stroke, contributing
significantly to the global disease burden. Weather-based disease surveillance for healthcare
providers is lacking. Hence, we aimed to forecast the number of daily hemorrhagic stroke admissions
based on meteorological parameters by applying machine learning models.

#### Methods: 
Hemorrhagic stroke patients diagnosed at the University Medical Center Mannheim,
Germany between 01/2015–31/2021 were selected from the local data integration center (DIC).
Weather data were obtained from the German Weather Service (DWD). Complex geospatial matching
was performed based on clinic-, patients’ home- and closest tower locations at the time of admission.
Statistical- (Poisson), support vector- (SVR) and tree-based models (RF, XGB) were evaluated in
regression settings within time-stratified nested cross-validation (training-validation: 2015-2020, test
set: 2021) for daily, weekly and monthly number of combined bleeding cases.

#### Results:
2374 hemorrhagic stroke cases (50.5% female) were identified
including intracranial- (NICH=1613, 67.9%) and subarachnoid hemorrhages
(NSAH=761, 32.1%) with an average age of 63 years.

Seasonal peaks occurred (Fig. 3) during changing weather in winter
December-January (median=41, IQR: 35-44, p=1.25×10-5), in spring
(April, median=36, IQR: 30-38, p=9.42 × 10-6) and in fall in October
(median=35; IQR: 33.5-37.5, p=5.26×10-6). Interestingly, there was and
incidence peak also in the summer month of August (meadian=33, IQR:
31.5-36.5, p=4.82×10-6).

Baselinemodels
* The Poisson model revealed a negative association between $P_{mean}$ (RR=0.76,95%CI=0.62-0.91,p=0.004)and a positive with $T_{max}$ (RR=1.26,95%CI=1.06-1.49,p=0.005) for daily $N_{bleeding}$.
* The GAM model identified $P_{max}$ and weekday as the $1^{st}$ and $2^{nd}$ most significant variables.

Machine learning models:
* XGB surpassed other machine learning models, registering lower MAE and RMSE values of 0.73 and 0.98, respectively.
* $P_{max}$, lag2 $V_{mean}$ windspeed and $P_{min}$ emerged as top predictor in the XGB model.
* Additionally, cold stressors that indicated by low $T_{max}$ <7 °C and decreased sunshine duration lag7 $S_{total/day}$ <13h were positively associated with $N_{bleeding}$.

#### Conclusions:
Our study provides a generalizable, disease-agnostic framework for real-time resource allocation and optimized therapy planning – not just for neuroradiological emergencies.
