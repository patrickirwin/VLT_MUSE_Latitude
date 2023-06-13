# VLT_MUSE_Latitude
Repository of data files associated with VLT/MUSE Latitudinal Variations Paper

This repository contains files used to determine the Latitudinal Variation of aerosols and abundances in Neptune's Atmosphere from observations made in 2019 with the MUSE instrument at the Very Large Telescope (VLT) in Chile and reported in J. Geophys. Res.

The data files are as follows.

For Figure 1:

The MUSE data are available from https://doi.org/10.5281/zenodo.7594682. The natural colour image is reproduced here, with and without gamma correction in the files:
Neptune_MUSE_sRGB_deconv.jpg and Neptune_MUSE_sRGB_deconv_Gamma.jpg 

difference_spectra_edit.txt - lists the difference spectra of NDS-2018, DBS-2019 and SBS features. The units are I/F.
For Figure 2:

profile_nds.txt - atmospheric T/P/vmr and cloud profiles used for Minnaert-fit to 10-20N latitude band. The units of cloud amount are particles/gram, but the profiles have been normalised such that total integrated cloud amount is the integrated opacity of the cloud at 800 nm.
amounts_nds.txt - the actual path layers and amounts used in the radiative transfer calculation.
data_summary_nds.txt - a summary of the refractive index data of the three aerosol types and the cloud opacities for the reference Minnaert fit to the 10-20N latitude band and also to the NDS-2018 spectrum and the expected spectrum at the NDS-2018 location.
scat_summary_NDS.txt - summary of the particle scattering properties. This also appears in Supplementary tables 2 - 6.
compare_spectra_nds.txt - the spectra fitted to in the NDS-2018 region and the expected background spectrum.
For Figure 3:

profile_dbs.txt - atmospheric T/P/vmr and cloud profiles used for Minnaert-fit to 5-15N latitude band. The units of cloud amount are particles/gram, but the profiles have been normalised such that total integrated cloud amount is the integrated opacity of the cloud at 800 nm.
amounts_dbs.txt - the actual path layers and amounts used in the radiative transfer calculation.
data_summary_dbs.txt - a summary of the refractive index data of the three aerosol types and the cloud opacities for the reference Minnaert fit to the 10-20N latitude band and also to the DBS-2019 spectrum and the expected spectrum at the DBS-2019 location.
scat_summary_DBS.txt - summary of the particle scattering properties. This also appears in Supplementary tables 2 - 6.
compare_spectra_dbs.txt - the spectra fitted to in the DBS-2019 region and the expected background spectrum.
