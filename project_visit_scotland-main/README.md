# Visit Scotland Tourism Data - CodeClan Final Project
<br>
<h2> Project Brief </h2>
<br>
<h4>
<p>VisitScotland.com is the official consumer website of VisitScotland, Scotland’s national tourist board.</p>
<p>Working closely with private businesses, public agencies and local authorities, we work to ensure that our visitors experience the very best of Scotland and that the country makes the most of its outstanding tourism assets and realises its potential.</p>
To do this, VisitScotland:
<ul>
  <li>markets Scotland to all parts of the world to attract visitors.</li>
  <li>provides information and inspiration to visitors and potential visitors so they get the best out of a visit
to Scotland.</li>
  <li>provides quality assurance to visitors and quality advice to our industry partners to help the industry
meet - and strive to exceed - visitors’ expectations.</li>
</ul>
<h2> Data Sources </h2>
<p> There were 6 open source data sets provided with the brief and are all available on statistics.gov.scot in association with Visit Scotland.
<br>
In addition, an external data set was sourced to analyse international data. This was taken from the Scottish Tourism Observatory and is also open source.
<br>
The data sets that were used are:
<ul>
  <li>activities.csv</li>
  <li>demographics.csv</li>
  <li>locations.csv</li>
  <li>transport.csv</li>
  <li>regional_tourism.csv</li>
  <li>accommodation_occupancy.csv</li>
  <li>international.csv</li>
</ul>
<h2> Project Assumptions </h2>
<p> The data provided with the brief was reported in a heavily summarised format, which limited both the analysis and model building potential.
Values were reported in a single column for multiple units of measurement and there were also some anomalies in the data, due to the reporting of 'All'.
When looking at the totals of the `activities`, `demographics`, `locations` and `transport` data, it became apparent that the summed values of 'All' were
the same. However, when looking at the summed values of the data when 'All' is filtered out, only the `transport` data matched the expected results for summarising
the not 'All'. Therefore, when completing analysis of summarised data, it was decided to filter all of the 'All' values out of the data.</p>
<h2> Analysis </h2>
<p> A full analysis of the business questions was completed and is available in the relevant folder in a Jupyter Notebook. This also includes a section on 
modeling.</p>
<h2> Presentation </h2>
<p> There is an accompanying presentation that addresses selected business questions, modeling and further work</p>
