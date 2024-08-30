# SLAC-ATLAS-ITk-summer-project

b/c impact parameters:
Phia and Noe attempted to make a first approximation using Monte Carlo to show how resolution impacts the ability to distinguish between the impact parameters for b and c hadrons. 
To do this we first sampled from an exponential distribution for the particle's lifetime and translated that to an impact parameter as ~c *lifetime. 
For each point sampled we then smeared it assuming the resolution follows a gaussian distribution centered at the point sampled with a given resolution. 
What we then wanted to know is how many b's versus c's we could count from a given impact parameter onwards, where that point defines a cutoff. We integrated from this cutoff point and compared the amount of b's to c's for a given resolution. 

RTD readout: 
reads RTDs on the dummy ring via the raspberry pi and sends it to Grafana. 
