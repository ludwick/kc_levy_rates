# kc_levy_rates

A github project with CSV formatted versions of King County (Washington) property levy rate data

These files were created from the PDFs offered on the [King County Assessor's website](https://www.kingcounty.gov/depts/assessor/Reports/levy-rate-info.aspx). The "Collective Rates" documents specifically were downloaded.

Then this [Tabula tool](https://github.com/tabulapdf/tabula) was used to create a basic CSV which had two columns of data. The second column was appended onto the first and intermediate extra "header" rows were removed. The columns in each file are:

* CITIES - The city for that rate. Note that if this value is blank, then the most recent value in a preceding row is the correct one.
* Levy Code - The four digit code for that jurisdiction. This code cross references to Parcel data records.
* Levy Rate - The normal assessment rate per $1000 value.
* Senior Rate - The senior rate per $1000 value.

Enjoy!
