# SALSA - Solar Applied pLanetary dataSet cAlibration
SALSA is a python tool that calibrates planetary spectral data in Mid- to Far-Ultraviolet wavelengths (110 – 300 nm), using data from the Solar Stellar Irradiance Comparison Experiment (SOLSTICE) on NASA’s Solar Radiation Climate Experiment (SORCE). It is designed to allow planetary scientists to input their spectra (in units of kR/Å) of a planet or moon and SALSA will produce a number of results. The first option is for SALSA to return a high-resolution solar spectrum for the time being queried. The second is for SALSA to produce the convolution of this solar spectrum onto a point spread function of an ultraviolet instrument in operation, the user can use the few built-in PSFs or they can input their own PSF parameters as well. Lastly, SALSA will divide the planetary spectrum ( I ) by the solar spectrum ( F ) to produce the object’s reflectance ( I / F ). This can then be used to study properties of the object such as surface or atmospheric composition.

