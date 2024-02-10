# SolaxToPVOutput

Upload the latest reading from SolaxCloud <https://www.solaxcloud.com/> to PvOutput <https://pvoutput.org>

Pvoutput Api: <https://pvoutput.org/help.html#api-addstatus>
Solaccloud Api: <https://www.solaxcloud.com/#/api> (you must be logged in)

How to use:

* Copy config.yml_rename_this to config.yml and fill with your own values
  * PVoutput API key and system id
  * Solaxcloud registration number (not the serial number of the wifi module) + Api key.
  * For debugging purposes one can set the logging level in the YAML file. Default is Warning.
* Install python dependencies: pip install pyyaml requests
* Code will upload data every 5 minutes

A log is created named solaxtopvoutput.log
