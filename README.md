## Realtime Index-Free Single Source SimRank Processing on Web-Scale Graphs PVLDB2020

### NOTE: please click Releases and download simpush-release-code.zip to get the codes with dblp dataset.

Please cite our papers if you choose to use our code.

```
@article{DBLP:journals/pvldb/ShiJYXY20,
  author    = {Jieming Shi and
               Tianyuan Jin and
               Renchi Yang and
               Xiaokui Xiao and
               Yin Yang},
  title     = {Realtime Index-Free Single Source SimRank Processing on Web-Scale
               Graphs},
  journal   = {PVLDB},
  volume    = {13},
  number    = {7},
  pages     = {966--978},
  year      = {2020}
}
```


### Tested environment
- Ubuntu
- G++ 7.4

### Run:
make
./simpush -f dblp -qn 50

### Evaluation:
g++ -std=c++11 cal_evalaute.cpp -o eval
bash run_dblp_eval.sh

