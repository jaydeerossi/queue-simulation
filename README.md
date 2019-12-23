# queue-simulation
### Summary of Problem and Solution
This simulation model can be used for low-cost experimentation on real-time reporting performance. The basic scenario is that  reports are processed by a queue's daemons in a FIFO manner. If reports are experiencing long wait times, the issue can be mitigated by removing reports from the queue, or by changing queue settings like the number of daemons available. This tool can ingest two weeks of historical report run data, and estimate how the wait times would change as a result of mitigation steps like those just mentioned. This prospective validation is a significant improvement over the status quo, where queue changes would be executed ad hoc, and then the impact of those changes would be assessed over the following days and weeks. 

### Repo structure
Internal Explanation - Queue Simulation.rmd - this Rmd is closely commmented to expain to potential users how the simulation works. By understanding a few key features and input fields, anyone can run simulation experiments for themselves.

Customer Template - Queue Simulation.rmd - this Rmd is for those who have read the internal explanation and would like to provide queue management recommendations based on their simulation findings. The Rmd is structure to show key code snippets and visualizations interspersed with commentary. 
