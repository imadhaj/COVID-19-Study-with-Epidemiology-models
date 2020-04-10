# COVID-19 Study with Epidemiology models

In this project, we are going to Study COVID-19 with Epidemiology models, based on 3 model:
- SIR model 
- SIER Model 
- Modified SEIRD model considering quarantine lockdown (SEIRD-Q)  

source of method : 
- https://www.lewuathe.com/covid-19-dynamics-with-sir-model.html
- https://www.who.int/bulletin/online_first/20-255695.pdf
- https://arxiv.org/pdf/2003.09909.pdf
- https://fpmag.net/wp-content/uploads/2020/01/Imperial-2019-nCoV-transmissibility.pdf?fbclid=IwAR2JLoNIK1CffTrBzcfILeGafEDKYYM4KMr9ASfxlcO02lIZdYGxvgPnbfU

This notebook presents a simple "study", more like as an exercise, of how a data conciliation can be performed on Epidemiology models. This kind of approach can be adapted for other cases that have Dynamical Systems as mathematical model 

Contents :

- Importing library
- Loading Data from :
  * https://www.kaggle.com/imdevskp/corona-virus-report
  * https://www.kaggle.com/fernandol/countries-of-the-world
- Data cleaning/ Data preprocing (global data visualization / comparison between results from Algeria and Morocco)
- Programming SIR/SEIR-based models in Python ( you will find a pdf explaining the methods with this file)
- Predictions


Source of code : This study is done by Diego Volpato (https://www.kaggle.com/volpatto) on different countries. I tried to adapt the methods on the Morocco dataset, and to implement the epidemiology models on our case.

Interesting remark : COVID-19 is a real thing, don't propagate results and data as conclusive if YOU ARE NOT A SPECIALIST IN THE FIELD.

Finally my thanks to Mohamed BECHAR(https://www.linkedin.com/in/mohammed-bechar-09216b10a/) and Younes LAHOUIR(https://www.linkedin.com/in/younes-lahouir-519034103/)
