# ATOOP-Final-Project
Final project in Advanced Topics in Object-Oriented Programming<br/>
**Description:**<br/>
This project deals with the time-dependent simulation of vessels, and is designed to use the [Controller-View-Model paradigm](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller).  
<br/>
**Model** : This is a single object which is required to be defined in the Singleton format; It is his responsibility to monitor the world of simulation in all its aspects, from time management to object storage. In particular, it must hold using pointers all the vessels and ports participating in the simulation, and provide access services to them. In addition, the object is responsible for providing update services for the view object.<br/>
**Port**:This is a simulation object with a fixed location and fuel reservoirs (without storage limit), and it is the responsibility of unloading, loading, and refueling a vessel. 
