# m35_psf
Trying to get PSF Photometry running on K2 M35 data

We are testing out the photutils PSF Photometry package on some K2 data from the m35 cluster. We chose one variable star with an average brightness to look at. Using the Gaia catalog, we found stars with a good brightness that were somewhat isolated to base the model on. Once we made the model, we fit it to the chosen star to estimate its flux in each of three images. We compared those results with the fluxes estimated using aperture photometry. The PSF result shows a much larger variation than the aperture photometry. 
