# DataScience
Code and documentation about looking at how We Vote is used by voters.

The analytics file which contains the Python codes for graphs.
The format of these files are .ipynb
These files can be opened in Jupyter notebook or Google Colab.
For Jupyter Notebook you will need to install ANACONDA on your local machine.
Google Colab can be used online in the browser.
The file contains code cells which need to be run to get the graphs as an output.


voter_sitewide.ipynb has graphs for the data taken from this link https://api.wevoteusa.org/apis/v1/docs/sitewideVoterMetricsSyncOut/

daily_sitewide.ipynb has graphs for the data taken from this link https://api.wevoteusa.org/apis/v1/docs/sitewideDailyMetricsSyncOut/

analyticsActionSyncOut.ipynb has graphs for the data taken from this link https://api.wevoteusa.org/apis/v1/docs/analyticsActionSyncOut/

issues_description.ipynb has the code for the graph of issue_description.json file
issue_decription.json has been downloaded from the link https://api.wevoteusa.org/apis/v1/docs/issueDescriptionsRetrieve/
First download the file from the link and edit the json file.
remove the {"status": "ISSUES_RETRIEVED", "success": true, "issue_list": from the start and } from the end.

elections_retrieve.twb is a tableau file which has graphs of elec.json
elec.json has been downloaded from the link https://api.wevoteusa.org/apis/v1/electionsRetrieve/
First download the file from the link and edit the json file.
remove the  {"status": "", "success": true, "election_list":  from the start and } from the end.
