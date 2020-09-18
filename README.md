## Impact of socio-political incidents on the spread of COVID-19 (Ethiopia)
![Figure 1](https://raw.githubusercontent.com/nahomneg/week3/master/Plot.PNG)

## Business Need
Ethiopia, like many other countries across the globe, is faced with the challenge of mitigating
and controlling a highly transmittable disease in the name of COVID-19. As COVID-19 is rapidly
spreading rapidly, short-term modeling forecasts provide time-critical information for decisions
on containment and mitigation strategies.

## Objectives
The project uses a combination of an established epidemiological model (SIR) and Bayesian inference. It analyzes the time dependence of the effective growth rate of new infections and predicts the number of new cases until Aug 16.

## Procedure
The model works by first taking government interventions and political instabilities that might
have an effect to the transmission rate into consideration. Then it creates time intervals that
correspond to the incidents. This is followed by making use of the confirmed COVID19 cases
and trying to come up with the best transmission and recovery rates that correspond to the
data in each time interval. This is achieved by making use of a technique called Bayesian
Inference. Once we have the approximation of the transmission rate, it is possible to forecast
the number of new or total cases. Our model works by adapting a science paper
named Inferring change points in the spread of COVID-19 reveals the effectiveness of
interventions published by Jonas Dehning Et Al.

## Limitations

The analysis has limitations arising from both the shortcomings of SIR and the recorded data.
SIR requires well mixed, homogeneous populations. In a real population, infection rates and
times vary with age. The model we used does not account for the time a person is infected but
not able to transmit the disease (Incubation Period). The following are some of the problems that have a significant
negative impact on the reliability of the data.
- Ethiopia, as a developing country is struggling with lack of equipped diagnostics with
appropriate instruments and testing kits. 
- . Civil unrests also resulted in days with no tests
conducted.
- Ethiopia applied most of the interventions before the community spread began. This resulted in only one government intervention in the analysis

-  Some people choose to fight corona without going to the hospital which can result
in their cases being reported.

## Observations

Ethiopia applied most of the interventions before the community spread began. The success of
those actions is verified by the plot on Figure 1. There is a relatively gentle rise for the first few
months as opposed to the expected steep increase. On the contrary, an incident on June 30
proved to be catastrophic and is verified by steep increase after July 10. This shows that when
faced with highly infectious diseases in the future, countries should not underestimate the
importance of early interventions even if it might pose economic instability. In addition
to that, countries across the globe can learn the devastating the impact of uncontrollable civil
unrests and try to resolve everything that may lead to unrest by all means necessary.
