# SC jail deaths
No state agency comprehensively tracks deaths in the custody of locally-run jails and detention facilities in South Carolina, and data compiled by the federal government isn't made public on the facility level. The Island Packet compiled the most comprehensive public count of these deaths, dating back to 2009, from several sources. 

The newspaper's dataset shouldn't be treated as a complete tally of deaths, given the limitations in the data sources outlined below. However, it includes more deaths than the federal Bureau of Justice Statistics reported [state-level tally up to the year 2018](https://bjs.ojp.gov/content/pub/pdf/mlj0018st.pdf). Asked about the discrepancy, a DOJ spokesperson said BJS uses strict definitions to count "in custody" deaths (excluding, for example, inmates not fully booked into a jail, or those released from custody prior to death) and also noted that some facilities could have not reported deaths to BJS in any given year.

The Island Packet's dataset is comprehensive between Jan. 1, 2009 and June 15, 2021 -- the cutoff for some records requests used in this reporting -- but includes deaths after that date identified through other sources. The newspaper did not file public records requests for deaths in custody with each of the roughly 60 local jails and detention facilities in the state. However, FOIA requests were sent to 11 facilities where reporters weren't initially able to identify any in-custody deaths dating back to 2009 from other sources, or that appeared not to be submitting regular documentation of deaths to state agencies.  

View the data dictionary below for column descriptions. Wherever possible, reporters identified the primary source where a death was identified and what information was added through supplemental sources. Deaths include inmates who died inside jails and deaths of inmates receiving medical care outside of a detention facility, but not deaths of inmates monitored by jails but released as part of a home incarceration program in some counties. Missing information for a specific death indicates it was not listed on a primary source document and reporters couldn't locate it in news reports or other sources. Full cause and manner of death wasn't available in each case, and reporters included as much information as was available on documents, however specific.

If you have questions about this data, find incorrect information in it or know of deaths that were not included, please email Lucas Smolcic Larson at [SCjaildeaths@gmail.com](mailto:scjaildeaths@gmail.com)

## Data Dictionary

| Variable               | Description                                                                                                                    |
|------------------------|--------------------------------------------------------------------------------------------------------------------------------|
| `main_source`          | which major records were used to identify this death: SCDC = SCDC Form 8-2; Reuters = Reuters News data; SCDPS = annual arrest-related death research reports; DCRA = DCR-1A form maintained by SCDPS; Local media = local news reports; Lawsuit = wrongful death lawsuit complaint |
| `date of death`        | date of inmate death           |
| `time_of_death`                | time of inmate death, if available   |
| `first_name`                 | inmate's first name      |
| `mid_name`                 | inmate's middle name         |
| `last_name`               | inmate's last name    |
| `suffix`  | suffix to inmate's name   |
| `SCDC_form_date`      | date jail completed SCDC Form 8-2 (if present)  |
| `county`     | county where jail located    |
| `gender`         | inmate's gender          |
| `race`     | inmate's race       |
| `age`     | inmate's age     |
| `dob`     | inmate's date of birth    |
| `yob`         | inmates year of birth (if dob not available)    |
| `cause_detail`     | Details about the cause of death       |
| `jail` | name of jail     |
| `date incarcerated`  | date inmate incarcerated   |
| `time_incarcerated`      | time inmate incarcerated    |
| `arresting_charges`  | charges when inmate was booked     |
| `custody_status`      | sentenced or pretrial at time of death  |
| `officer_on_duty`     | # of officers on duty at time of death (from SCDC Form 8-2)  |
| `inmate_count`         | # of inmates at time of death (from SCDC Form 8-2)     |
| `news_coverage`             | links to news coverage of the death |
| `info_from_media`             | which fields were filled using information from local media reports and other secondary sources |

## Data sources
### S.C. Department of Corrections Form 8-2
South Carolina [law requires](https://www.scstatehouse.gov/query.php?search=DOC&searchtext=24%209%2035&category=CODEOFLAWS&conid=36780581&result_pos=0&keyval=16879&numrows=10#OCC1) local detention facilities to report to SCDC within 72 hours of a death of an inmate, whether incarcerated or otherwise in their custody. The Island Packet obtained these documents through S.C. Freedom of Information Act requests for records dated from 2009 to June 15, 2021. Reporters manually entered the forms' fields into the dataset. Many forms were incomplete or lacking a cause of death and reporters supplemented missing information with other sources. The Island Packet excluded deaths reported for inmates in the custody of home incarceration programs in Horry and Greenville counties. At least 30 deaths identified by the newspaper did not have a corresponding SCDC form. For a handful of cases, jails sent the legally required forms to SCDC only after a reporter asked the agency about those specific deaths, and it followed up directly with the jail.

### DCR-1A forms maintained by the S.C. Department of Public Safety
Implementation of the federal Death in Custody Reporting Act of 2013 began at the state-level in 2020 through SCDPS. The DCRA requires reporting of a broad swath of deaths in law enforcement custody, including deaths in local jails. In South Carolina, local coroners complete [DCR-1A forms](https://scdps.sc.gov/sites/default/files/Documents/ohsjp/Form%20DCR-1A.pdf) and submit them to the SCDPS Office of Highway Safety and Justice Programs. The Island Packet obtained these forms for late 2019 and calendar year 2020 from The News & Observer, which requested them via FOIA. The Packet also submitted an additional FOIA request for forms submitted for deaths taking place in 2021, up to June 24. Taken together, these forms included just a subset of the jail deaths reporters identified from other sources (for 2020 it was 2 out of 23). A SCDPS spokesperson said the agency would follow-up with local coroners offices as the reporting process is new and added that all 2020 data collection was still considered preliminary. 

### Annual reports from University of South Carolina researchers and the S.C. Coroner's Association 2009 - 2014
Between 2003 and 2014, SCDPS contracted with USC's Department of Criminology and, for some years, the S.C. Coroner's Association to collect data for the U.S. Bureau of Justice Statistics [Arrest-Related Deaths (ARD)](https://bjs.ojp.gov/data-collection/arrest-related-deaths-ard) program, which was suspended in 2014. Some of these reports are available on the [SCDPS website](https://scdps.sc.gov/ohsjp/stats/DeathsInCustody) and reporters obtained the rest directly from the lead author at USC. These yearly reports, drawn from local coroners and media reports, list deaths that occured prior, during or following an arrest, but pre-arraignment. This data collection captures some deaths in local jails and the authors note they erred on the side of inclusion even though deaths in custody post-arraignment were subject to a separate BJS data collection effort. 

### Jail death data published by Reuters News
Reuters News submitted public records requests to the 10 biggest jails in every state for deaths occurring from 2008 to 2019 for a [multi-part investigation published last year](https://www.reuters.com/investigates/section/usa-jails/). Their data is available for each state [here](https://www.reuters.com/investigates/special-report/usa-jails-graphic/). The Island Packet used it to identify deaths missing in other data sources and also supplement information for already identified deaths. The Reuters data included deaths from the Aiken County Detention Center, Anderson County Detention Center, Berkeley County Detention Center, Sheriff Al Cannon Detention Center (Charleston County), Greenville County Detention Center, J. Reuben Long Detention Center (Horry County), Lexington County Detention Center, Alvin S. Glenn Detention Center (Richland County), Spartanburg County Detention Center and York County Detention Center.   

### Jail deaths tracked by The Huffington Post
Between July 13, 2015 and July 13, 2016, The Huffington Post tracked jail deaths nationwide following the death of Sandra Bland in Texas. Their database is [available here](https://data.huffingtonpost.com/2016/jail-deaths) and was used to identify additional deaths in South Carolina during that period.

### South Carolina court records and local media reports
The Island Packet also used wrongful death and personal injury lawsuits filed in South Carolina courts to identify and supplement information on jail deaths. When a local news story or lawsuit is the primary source for a specific death, it is identified as such in the data. When only certain information was obtained from local news reports or court records, it was noted in the dataset. 

### Reports maintained by local jails an obtained via FOIA
Reporters filed records requests with eight local jails for which they could not initially identify in-custody deaths from other sources. The Island Packet used request language similar to that employed by Reuters journalists for their national investigation ([published by MuckRock](https://www.muckrock.com/news/archives/2021/mar/09/reuters-local-jails-data-webinar/)) to cover deaths occurring between Jan. 1, 2009 and June 20, 2021. The Island Packet also filed FOIA requests with five additional jails that appeared to not be consistently sending Form 8-2s to SCDC. Three of them responded in advance of publication. The result of those requests are outlined below and included in the dataset.

| Jail               | Responsive records                                                                                                                    |
|------------------------|--------------------------------------------------------------------------------------------------------------------------------|
| Allendale County Detention Center   | Jail administrators report no deaths for the time period requested |
| Bamberg County Detention Center   | Jail administrators report no deaths for the time period requested |
| Darlington County Detention Center   | Jail administrators provided reports for three deaths and oral confirmation of a fourth |
| Hampton County Detention Center   | Jail administrators report no deaths for the time period requested  |
| Marion County Detention Center   | Jail administrators provided report of one death |
| McCormick County Detention Center   | Jail administrators report no deaths for the time period requested  |
| Williamsburg County Detention Center   | Jail administrators report no deaths for the time period requested  |
| Saluda County Detention Center   | Jail administrators report no deaths for the time period requested  |
| Oconee County Detention Center   | Jail administrators reported provided reports of six deaths |
| Florence County Detention Center   | Jail administrators provided reports for nine deaths |
| Georgetown County Detention Center   | Jail administrators provided reports for six deaths  |
| Chesterfield County Detention Center   | Jail administrators did not respond in advance of publication  |
| Colleton County Detention Center   | Jail administrators did not respond in advance of publication |





