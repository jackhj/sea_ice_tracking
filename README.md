# sea_ice_tracking
Contains development python code for tracking sea ice via a simple image tracking algorithm.

To track sea ice we employ SSMI satellite-derived brightness temperatures.
Daily temperatures are binned to a matrix of 632 columns x 664 rows.

Using pyspark, running on databricks with ipython notebook, we aim to track ice flow through maximizing correlations between daily measurements.
