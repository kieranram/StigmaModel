# StigmaModel
Replicating results from A Dynamic Computational Model of Social Stigma, Chang 2019

In this simplified model of a society, a certain fraction of the population possess a stigmatizing trait. At the beginning of a run of the model, 
a certain fraction of the stigmatized agents choose to reveal their stigmatizing trait, while the remaining ones hide it. Other agents are either 
against the stigma, neutral, or accepting. They switch between states based on what type of agent they are, a compassionate one or a conforming one. 

Chang's model showed that societies strongly skewing either compassionate or conformist will not achieve as wide acceptance as those with a balance
between the two types. I attempt to replicate those results. 


TODO: 
Figure out why results aren't matching. 
Seems like change stops propagating very quickly in my network, which also has a wider
degree distribution than the original. Assignment mechanicsm is same, so might have to 
do with RNGs. 

Citation: 
Chang, Myong-Hun and Harrington, Joseph (2020) 'A Dynamic Computational Model of Social Stigma' Journal of Artificial Societies and Social Simulation 23 (2) 1 <http://jasss.soc.surrey.ac.uk/23/2/1.html>. doi: 10.18564/jasss.4225
