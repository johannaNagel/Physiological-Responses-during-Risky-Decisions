# Physiological-Responses-during-Risky-Decisions
Thie repository contains the code for the master thesis about the physiological responses during risky decisions.

## Abstract of the thesis:

Emotions and decisions influence each other. Emotional states shape choice behavior, while decisions themselves can trigger physiological responses. Building on this research, this study examines whether market mechanisms such as price volatility and deviations from fundamental value influence electrodermal activity (EDA) as an indicator of risk. Various statistical methods were used to examine whether high risk, operationalized by high volatility or large deviations from fundamental value, is associated with increased EDA during the decision-making process and whether this association depends on transaction type or decision phase. These results show weak associations between EDA and fundamental deviations, which became stronger in some cases when contextual factors were taken into account. Volatility, on the other hand, showed no systematic influence. Overall, the mechanisms had a slightly stronger effect on skin conductance rate and skin conductance level. Combined analyses revealed individual interaction effects, particularly in the case of purchases. Predictive models confirmed that EDA alone has limited value for risk prediction, but performance improves substantially when combined with price information and transaction variables.



## Description of the files:
- **EDA_Findex_featuresExt**: This file contains the preprocessing and data collection steps for EDA signals. It removes noise and artifacts. It also decomposes the signal into SCL and SCR components. It also separates the signal into decision phases.
- **Risk_wo_Visualization_Final**: This file contains all risk measurement calculations, such as volatility and fundamental value.
- **Statistical_Test_Final**: This file contains all the statistical tests used to investigate the relationship between EDA and risk measurements. This notebook is too big; therefore, there is also a zip file and a file without the output (only the code). "Statistical_Tests_Final_withOut_Output" -> No output
- **Data_Visualization_Final**: This code contains all visualizations.

  
