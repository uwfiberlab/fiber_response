# fiber_response
This is a repository for exploring the effects of elastic wave type, propagation angle and fiber wrapping angle on distributed acoustic sensing (DAS) recordings

The notebook `fiber_response_baird.ipynb` is an example that reproduces the figures from Alan Baird's 2020 paper "Modelling the Response of Helically Wound DAS Cables to Microseismic Arrivals". The figure shows fiber response scenarios for P and S waves that arrive across a range of incidence angles (-180 - 180 deg) and over fiber wrapping angles from 0 - 90 deg (where 90 wrapping is a straight fiber). In general, helically wound cables reduce sensitivity of S waves relative to straight fibers for all propagation directions. It's also clear that at a wrapping angle of ~ 35 deg the fiber is essentially blind to S waves across all propagation directions. This could be useful for essentially turning a fiber into P / S wave filter. 

The notebook `orientation_factor_simple.ipynb` shows examples for the orientation factors that Brian Kennett describes in his 2022 paper "The seismic wavefield as seen by distributed acoustic sensing arrays: local, regional, and teleseismic sources". 
