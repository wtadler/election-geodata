# Georgia

Sourced from Georgia General Assembly's [Legislative and Congressional Reapportionment Office](http://www.legis.ga.gov/Joint/reapportionment/en-US/default.aspx) on 2017-03-11:

- **2012**
    - Source: Georgia Legislative and Congressional Reapportionment Office
    - tip from [Aaron Straus repo](https://github.com/aaron-strauss/precinct-shapefiles/tree/master/ga)
    - http://www.legis.ga.gov/Joint/reapportionment/Documents/VTD2012-Shape.zip
	- Downloaded 2017-04-01
- **2016 precincts, and a ton more stuff:**
    - Source: [Georgia Legislative and Congressional Reapportionment Office](http://www.legis.ga.gov/Joint/reapportionment/Documents/VTD2016-Shape.zip)
	- Downloaded 2017-03-11
- **2016** precincts with election results. Citation: _Florida Election Science Team, 2018, "2016 Precinct-Level Election Results", [https://doi.org/10.7910/DVN/NH5S2I](https://doi.org/10.7910/DVN/NH5S2I), Harvard Dataverse, V2._
  - Downloaded and posted on 2018-08-22 by [Will Adler](https://github.com/wtadler), [Princeton Gerrymandering Project](http://gerrymander.princeton.edu/)
  - Columns reporting votes follow a standard label pattern. For example, **G16PREDCli**:
    - Character 1 is G for a general election, P for a primary.
    - Characters 2 and 3 are the year of the election.
    - Characters 4–6 represent the office type:
      - GOV - Governor
      - H## - U.S. House, where ## is the district number. AL: at large.
      - LTG - Lieutenant Governor
      - PRE - President
      - PSC - Public Service Commission
      - RRC - Railroad Commissioner
      - USS - U.S. Senate
      - Character 7 represents the party of the candidate, such as D and R. See below for specific codes; note that third-party candidates may appear on the ballot under different party labels in different states.
      - Characters 8–10 are the first three letters of the candidate's last name.
  - Other codes:
    - President
      - G16PREDCli - Hillary Clinton (Democratic Party)
      - G16PRELJoh - Gary Johnson (Libertarian Party)
      - G16PRERTru - Donald J. Trump (Republican Party)
    - U.S. Senate
      - G16USSDBar - Jim Barksdale (Democratic Party)
      - G16USSLBuc - Allen Buckley (Libertarian Party)
      - G16USSRIsa - Johnny Isakson (Republican Party)
    - Georgia Public Service Commission
      - G16PSCLHos - Eric Hoskins (Libertarian Party)
      - G16PSCREch - Tim Echols (Republican Party)
    - Election results from the [Georgia Elections Division](http://results.enr.clarityelections.com/GA/63991/184321/en/summary.html)
    - Precinct shapefile from the [Georgia General Assembly Reapportionment Office](http://www.legis.ga.gov/Joint/reapportionment/en-US/default.aspx)
    - Chattahoochee County had 4 precincts in the original shapefile, but only reported countywide, so these were merged.