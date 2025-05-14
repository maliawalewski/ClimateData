# Climate Change Visualization with CMIP6 Data

This project visualizes projected climate conditions (2020–2049) across four future greenhouse gas concentration scenarios using CMIP6 ensemble mean data.

## Datasets & Methods
- **NetCDF climate datasets** from the CMIP6 model ensemble
- Scenarios: `ssp1-2.6`, `ssp2-4.5`, `ssp3-7.0`, and `ssp5-8.5`
- Variables plotted:
  - Near-Surface Air Temperature (`airTemp`)
  - Precipitation
- Visualized using:
  - `xarray` for NetCDF manipulation
  - `Cartopy` for geospatial plotting
  - `Matplotlib` for visual presentation

## Features
- Custom plotting function to project climate data on global maps
- Plots for each scenario with consistent color scales and formatting
- Includes `borders`, `coastlines`, and global extent setup

## Takeaways
- Clear warming trend across scenarios, especially `ssp3-7.0` and `ssp5-8.5`
- Useful for communicating how climate outcomes vary with emissions pathways

## Tools Used
- Python
- `xarray`, `matplotlib`, `cartopy`, `numpy`

