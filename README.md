# Spring2018BigDataProject1

## notes and dependencies fuuuuuu
- sqlite3
- numpy
- pymongo
- django?? not set up yet
- redis?? but downloaded so idk
- needs stress tetsitn gomg 

## adkbase.py

main running program, will tell computer to run servers, just run adkbase.py. also will kill servers at end so yearh

## sqltest.py

uses patient.db, can run by itself without servers. will check if data has already been stored, and upload thee newestdata(double check if this is true?). Stores data for entrez_ids_genesybmol.csv and patiensts.csv?


## testred.py and checkredis.py

uses redis. first run ./redis-stable/src/redis-server, then run checkredis.py. Data is stored in dump.rdb The file testred.py stores all the from PPI.csv into redis server. Currenly does not store uniquely, so running testred.py again will cause replaiction in data. 


## largecsvtest.py

checking if large csv file can be ued with csvreader; speed seems acceptable. Need to figure out storage for this. Using numpy for mean and std seems fine, need to seperate values based on diagnosis. 


## testxml.py

Still need to fucking deal with this. Can process XML files, but XML file so large that takes too much time. Need to decide what data to store, and with what format. Large XML file can't be uploaed bc too large, so make sure it is here locally before running this program. 