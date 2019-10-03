# Big Brain Meta-data

The MICA labs repo for all things Big Brain

## This repository currently contains

Intensity profiles (parcels x s, where s represents a equivolumetric surface)   
Statistical moments (parcels x m, where m represents the moments: mean, std, skewness and kurtosis)  
Microstructure profile covariance (MPC) matrices (parcels x parcels, in the same order as profiles)

### Construction notes

The profiles were generated by sampling Big Brain intensities along equivolumetric surfaces at 163,842 matched vertices per hemisphere.
Six equivolumetric surfaces were built between layer 1 and layer 4, and layer 4 and white matter. Thus the eighth surface is layer 4. 
Profiles and moments are available with and without regression for the midsurface y-coordinate. The BigBrain exhibits a strong anterior-posterior gradient in intensity values that is likely partially due to the coronal slicing and reconstruction, and partly to do with variations in cortical architecture. 

## References

* Paquola et al., (2019) - original deployment of the BigBrain profiling and microstructure profile covariance (https://doi.org/10.1371/journal.pbio.3000284)
* Paquola et al., (2019) - original implementation of moment-based characterisation of the depth profiles (https://doi.org/10.1101/706341)
* Amunts et al., (2017) - data descriptor of BigBrain (https://doi.org/10.1126/science.1235381)
ftp://bigbrain.loris.ca/
* Schaefer et al., (2018) - Schaefer parcellation (https://doi.org/10.1093/cercor/bhx179)
https://github.com/ThomasYeoLab/CBIG/tree/master/stable_projects/brain_parcellation/Schaefer2018_LocalGlobal
* Glasser et al., (2016) - Glasser parcellation (https://doi.org/10.1038/nature18933)

## Contact us

If you have any questions, please contact Casey Paquola at casey.paquola@mail.mcgill.ca 