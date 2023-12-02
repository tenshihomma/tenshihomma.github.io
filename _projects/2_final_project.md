---
name: Final Project
tools: [Python, HTML, vega-lite]
image: 
description: This is a "showcase" project that uses vega-lite for interactive viz!
custom_js:
  - vega.min
  - vega-lite.min
  - vega-embed.min
  - justcharts
---
Exploring the Electrifying World of Electric Vehicles
by Tenshi Homma

![Global electric vehicle stock by region, 2010-2020](assets/pngs/photo1.png)
Citation: IEA, Global electric passenger car stock, 2010-2020, IEA, Paris https://www.iea.org/data-and-statistics/charts/global-electric-passenger-car-stock-2010-2020, IEA. Licence: CC BY 4.0
![Global Electric car registrations and market share, 2015-2020Global electric vehicle stock by region, 2010-2020](assets/pngs/photo2.png)
Citation:IEA, Global Electric car registrations and market share, 2015-2020, IEA, Paris https://www.iea.org/data-and-statistics/charts/global-electric-car-registrations-and-market-share-2015-2020, IEA. Licence: CC BY 4.0

EV Data
<vegachart schema-url="{{ site.baseurl }}/assets/json/project_part3.json" style="width: 100%"></vegachart>

Citation:data.wa.gov,Electric Vehicle Population Data,https://catalog.data.gov/dataset/electric-vehicle-population-data

The World of Electric Vehicles
This automotive technology paradigm is embodied in the electric vehicle (EV). I will focus on EV growth statistics, and their contribution to a greener world. The purpose of this interactive visualization is to present this data in a way that is easy to understand so that even those with no knowledge of data analysis can make sense of it.

I have created a comprehensive interactive map that displays the global development pattern of EVs from 2010 to 2020. This visualization provides an at-a-glance view of various aspects of EV growth, including model diversity and increasing market penetration. By interacting with this chart, one can understand why different models have become more prevalent over time and how market forces have changed.

The photo “Global electric passenger car stock, 2010–2020” depicts how electric passenger cars rapidly multiplied worldwide. Such is this visual that depicts a decade of development, which shows the evolution of EV into everyday mobility solutions. It also highlights the growing global adoption of EVs.

The other important picture is “Global Electric Car Registrations and Market Share, 2015-2020,” which clearly shows how the EV market grew. The figure above illustrates both rising numbers and expanding proportions of registration for electric vehicles as part of the whole motor vehicle industry. This offers a view of how EV’s have been carving for themselves an important spot in the market of world cars as they reflect changing tastes in consumers’ preferences towards eco-friendly transport modes.

<!-- these are written in a combo of html and liquid --> 

<div class="left">
{% include elements/button.html link="https://github.com/vega/vega/blob/main/docs/data/cars.json" text="The Data" %}
</div>

<div class="right">
{% include elements/button.html link="https://github.com/jnaiman/online_cv_public/blob/main/python_notebooks/test_generate_plots.ipynb" text="The Analysis" %}
</div>

