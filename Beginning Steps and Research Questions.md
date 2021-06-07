# Beginning Steps and Research Questions

## Steps

1. Use downloaded Johns Hopkins data (lat/long) to map points on ArcGIS Pro
2. Once mapped, should be able to click on point to view attribute
3. Change symbology based on number of cases
4. Use regression modules (least square, geographically weighted)
5. Explore deep learning module
6. Watch `https://www.youtube.com/watch?v=ftFg_RRdYJI`
7. Explore social distancing data and masking data (exists in GIS format)
   - https://www.google.com/covid19/mobility/
   - https://coronavirus-resources.esri.com/datasets/disasterresponse::unacast-social-distancing-grades/about
   - https://www.nytimes.com/interactive/2020/07/17/upshot/coronavirus-face-mask-map.html
   - https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0249891#sec002
   - https://ourworldindata.org/covid-vaccinations
   - https://data.cdc.gov/Vaccinations/COVID-19-Vaccinations-in-the-United-States-Jurisdi/unsk-b7fc
   - https://data.cdc.gov/Vaccinations/COVID-19-Vaccinations-in-the-United-States-County/8xkx-amqh
8. Explore vaccination rate data (exists in GIS format)

## Research Questions

- What if we didn't have the vaccine right now? How would we model spread? Climate variables (temp, humidity, precip), population density, social distancing, masking. How is this different from real life? Can we change vaccination rates in the model?
- January is the cutoff for vaccinations (double check and should be different by location)
- Initial spread is March to Sep/Oct, check against Nov/Dec (crossfold validation)
- Compare dates across years