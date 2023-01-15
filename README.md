# ukhsa_serology

The UKHSA conducts a powerful survey of blood donors using Roche anti-S and anti-N assays.

These are published in graphical form in the [vaccine weekly surveillance reports](https://www.gov.uk/government/publications/covid-19-vaccine-weekly-surveillance-reports), but only in a rasterised graphical form. This repo contains code used to extract the anti-S levels from panels like:

![image](https://user-images.githubusercontent.com/19732295/212571036-b185918e-1e0c-47a5-b325-bf2630605e3f.png)

we can then combine these two datasets in ratios according to the anti-N level in the age group:
![image](https://user-images.githubusercontent.com/19732295/212571061-b5e126ed-c5a0-43d1-91b1-eadab051fcc2.png)
(we digitise those data with [Web plot digitiser](https://apps.automeris.io/wpd/)
