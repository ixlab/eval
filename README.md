# Evaluating Interactive Data Systems: Workloads, Metrics, and Guidelines
Lilong Jiang, Protiva Rahman, Arnab Nandi
SIGMOD 2018

## Citation
```
@inproceedings{jiang2018evaluating,
  title={Evaluating Interactive Data Systems: Workloads, Metrics, and Guidelines},
  author={Jiang, Lilong and Rahman, Protiva and Nandi, Arnab},
  booktitle={Proceedings of the 2018 International Conference on Management of Data},
  pages={1637--1644},
  year={2018},
  organization={ACM}
}
```

## Metrics Survey

### Query interface
  * Usability: 
    ```Proxied by query specification or task completion time~\cite{jagadish2007making,nandi2013gestural, yang2007analysis, kandel2011wrangler, javed2012gravnav, abouzied2012dataplay, zhang2012network, satyanarayan2014lyra, basole2013understanding, yang2011clues, dimitriadou2014explore, igarashi2000speed, singh2012skimmer, bakke2011spreadsheet, liu2009spreadsheet},  number of iterations, navigation cost~\cite{li2007nalix, basu2008minimum, kashyap2010facetor, kashyap2011effective}, miss times~\cite{jiang2015snaptoquery}, number and uniqueness of insights~\cite{rzeszotarski2014kinetica, faith2007targeted, willett2007scented, singh2012skimmer}, accuracy \cite{rahman2017ve,siddiqui2016effortless}, ability to complete tasks~\cite{yang2007analysis, key2012vizdeck, basole2013understanding, cao2011dicon, yang2011clues, heer2008generalized, singh2012skimmer, liu2009spreadsheet}```

  * Learnability: 
    ```Ability to learn user actions with instructions: \cite{nandi2013gestural, rzeszotarski2014kinetica, basole2013understanding}```

  * Discoverability: 
    ```Ability to discover user actions without instructions: \cite{jiang2015snaptoquery, nandi2013gestural, bakke2011spreadsheet, martin1995high}```

  * User feedback:
    ```Survey questions: \cite{nandi2013gestural, kandel2011wrangler, rzeszotarski2014kinetica, kamat2014distributed, willett2007scented, cao2011dicon, kashyap2010facetor, heer2008generalized, igarashi2000speed, liu2009spreadsheet}, case study~\cite{plaisant2004challenge, woodring2009multiscale, yuan2013dimension, yang2004value, bernard2013motionexplorer, seo2005rank, yang2003interactive, fisher2012trust, wei2012visual, ferreira2013visual, kosara2006parallel, mclachlan2008liverac}, design study~\cite{siddiqui2016effortless,sedlmair2012design},suggestions~\cite{biswas2013information, basole2013understanding, javed2012gravnav, satyanarayan2014lyra, wei2012visual, cao2011dicon, singh2012skimmer, khan2017data,rahman2017ve,siddiqui2016effortless,wongsuphasawat2016voyager,moritz2017trust}```

  * Behavior analysis:
    ```Sequences of mouse press-drag-release~\cite{javed2012gravnav}, event state sequence~\cite{lam2007session}```

### Performance:
  * Throughput:
    ```transactions / requests / tasks per second: TPC-C, TPC-E~\cite{tpc}, \cite{chan2008maintaining}```  

  * Latency: 
    ```execution time of the query or frame rate per second: \cite{jiang2015snaptoquery, kamat2014distributed, liu2014effects, liu2013immens, fekete2002interactive, lins2013nanocubes, kashyap2010facetor, dimitriadou2014explore, chan2008maintaining,khan2017data, vartak2014seedb,rahman2017ve,siddiqui2016effortless, hellerstein1997online}```

  * Scalability:
    ```performance with increasing data size, number of dimensions, number of machines: \cite{cooper2010benchmarking, liu2013immens, dimitriadou2014explore, kamat2014distributed,rahman2017ve,vartak2014seedb, kim2015rapid}```

  * Cache hit rate:
    ```\cite{battle2015dynamic, kamat2014distributed, tauheed2012scout}```