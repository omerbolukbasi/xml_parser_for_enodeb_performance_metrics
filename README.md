# Xml Parser For Ericsson Enodeb Performance Metrics
This code can be used to parse enodeb XML files of Ericsson in order to insert db in suitable format. 

Parser handles both old DUS format and new Baseband format. It takes the xml pm file as input. It converts the xml file into a Pandas Dataframe and processes it. After all fields are prepared the dataframe is written both in SQL and csv format. It can also be inserted to a proper db. 
