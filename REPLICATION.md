# [MC number] [Manuscript Title] Validation and Replication results
> In the above title, replace [Manuscript Title] with the actual title of the paper, and [MC number] with the Manuscript Central number (e.g., AEJPol-2017-0097)

You may want to consult [Unofficial Verification Guidance](https://social-science-data-editors.github.io/guidance/Verification_guidance.html) for additional tips and criteria.


Data description
----------------
### Analysis Data Files

> INSTRUCTIONS: List all provided filenames here. For large deposits, this can be done using the "Git Bash" program:
> > find . -name \*.dta
> will list all Stata datasets. Replace `dta` with `.Rdata` or any other extension to find other datafiles.

Example:
```
./Output_Empirical/data/census_shp/counties_coord.dta
./Output_Empirical/data/census_shp/counties_db.dta
./Output_Empirical/data/census_shp/state_coord.dta
./Output_Empirical/data/census_shp/state_db.dta
```

#### Deposit Metadata

- [ ] JEL Classification (required)
- [ ] Manuscript Number (required)
- [ ] Subject Terms (highly recommended)
- [ ] Geographic coverage (highly recommended)
- [ ] Time period(s) (highly recommended)
- [ ] Collection date(s) (suggested)
- [ ] Universe (suggested)
- [ ] Data Type(s) (suggested)
- [ ] Data Source (suggested)
- [ ] Units of Observation (suggested)


Data checks
-----------
> INSTRUCTIONS: When data are present, run checks:
> - can data be read (using software indicated by author)?
> - Is data in archive-ready formats (CSV, TXT) or in custom formats (DTA, SAS7BDAT, Rdata)?
> - Does the data have variable labels (Stata: run `describe using (name of DTA)` and check that there is content in the column "variable label")?
> - Run check for PII ([PII_stata_scan.do](PII_stata_scan.do), sourced from [here](https://github.com/J-PAL/stata_PII_scan) if using Stata) and report results. Note: this check will have lots of false positives - fields it thinks might be sensitive that are not, in fact, sensitive. Apply judgement.


Code description
----------------

> NOTE: In-text numbers that reference numbers in tables do not need to be listed. Only in-text numbers that correspond to no table or figure need to be listed.

Replication steps
-----------------

> INSTRUCTIONS: provide details about your process of accessing the code and data.
> Do NOT detail things like "I save them on my Desktop".
> DO describe actions   that you did  as per instructions ("I added a config.do")

Computing Environment

> INSTRUCTIONS: Please also list the software you used (specific versions). List only the ones you used, add any not listed in the examples:

- Stata/MP 16
- Matlab R2019a
- Intel Compiler 3.14152

Findings
--------
> For differences in figures, provide both a screenshot of what the manuscript contains, as well as the figure produced by the code you ran.

### Data Preparation Code

Examples:

- Program `1-create-data.do` ran without error, output expected data
- Program `2-create-appendix-data.do` failed to produce any output.
