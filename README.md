# Two simple and effective heuristics for minimizing the makespan in non-permutation flow shops

This repository contains supplementary data to the paper

Ritt, Costa, [Two simple and effective heuristics for minimizing the makespan in non-permutation flow shops](http://dx.doi.org/10.1016/j.cor.2015.08.001), Comp. Oper. Res., 66, 160–169, 2016.

## Abstract

 We propose a constructive and an iterated local search heuristic for minimizing the makespan in the non-permutation flow shop scheduling problem. Both heuristics are based on the observation that optimal non-permutation schedules often exhibit a permutation structure with a few local job inversions. In computational experiments we compare our heuristics to the best heuristics for finding non-permutation and permutation flow shop schedules, and evaluate the reduction in makespan and buffer size that can be achieved by non-permutation schedules.

## Supplementary data

* Detailed results on the comparison of variants of the proposed iterated greedy algorithm on the instances of Taillard in Table 2: [IGA](data/t2-iga.csv), [NPS+IGA](data/t2-nps+iga.csv), [IGA(LS)](data/t2-iga-ls.csv), [NPS+IGA(LS)](data/t2-nps+iga-ls.csv).
* Detailed results on the comparison of constructive heuristics on the instances of Taillard in Table 3: [NEH](data/t3-neh.csv), [KK2](data/t3-kk2.csv), [KM](data/Ruiz.Maroto%20(2005),%20T3.csv), [FF](data/Fernandez-Viagas,Framinan%20(2014),%20T1.csv), [NFS](data/t3-nfs.csv).
* Detailed results on the comparison to Lin and Ying (2009) and Rossi and Lanzetta (2013) on the instances of Demirkon et al. (1998) in Table 5: [Time LY/6](data/t5-ly6.csv), [Time 30nm²](data/t5-30nmm.csv), [results from the literature](data/Rossi.Lanzetta%20(2013),%20T4.csv).
* Detailed results on the comparison to Yagmahan and Yenisey (2010) and Rossi and Lanzetta (2013) on the first 28 instances of Taillard (1993) in Table 6: [Time 30nm](data/t6-30nm.csv), [Time 30nm²](data/t6-30nmm.csv), [results from the literature](data/Rossi.Lanzetta%20(2013), T3.dat).
* Detailed results on the instances of Taillard (1993) in Table 7: [Time 30nm](data/t7-30nm.csv), [Time 30nm²](data/t7-30nmm.csv).
* Detailed results on the comparison to state-of-the-art heuristics from the literature for permutation schedules on the instances of Taillard (1993) in Table 8: [Time 30nm](data/t8-3nm.csv), [Time 30nm²](data/t8-30nmm.csv), [our implementation of HGA](data/t8-hga.csv), results from the literature: [FF](data/Fernandez-Viagas,Framinan%20(2014),%20T1.dat), [NGV](data/Zobolas,etal%20(2009),%20T8.dat).
* Detailed results on the comparison of buffer sizes for permutation and non-permutation solutions on the instances of Taillard (1993) in Table 9: [permutation schedules](data/t9-permutation.csv), [non-permutation schedules](data/t9-non-permutation.csv).

## How to cite

```bibtex
@Article{Benavides.Ritt/2018,
  author = 	 {Alexander Benavides and Marcus Ritt},
  title = 	 {Fast heuristics for minimizing the makespan in non-permutation flow shops},
  journal =	 {Comput. Oper. Res.},
  year = 	 {2018},
  volume =	 {100},
  pages =	 {230--243},
  month =	 dec,
  doi = 	 {10.1016/j.cor.2018.07.017}
}
```
