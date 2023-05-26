
---
<p align="center" style="font-size: 30px;" > <strong>  Folder and Files Representation: </strong> </p>

---

</br>

* **bzip structures:** The bzip(276-351)wtATF4 structure files including bzip homodimer, G308A mutated bzip structure.
</br>

* **forcefields:** This folder has forcefield related files , forcefield information mentioned below.

  * </tab>  a99SBdisp.ff is force field used in MD simulation of bZIP, TAD and fulllengthATF4 protein(Activating Transcription Factor 4).

##### <p align = "center" style="font-size: 15px;"> <strong> Citation for forcefield</strong> </p>

        1. Water dispersion interactions strongly influence simulated structural properties of disordered protein states S Piana, AG Donchev, P Robustelli, DE Shaw The journal of physical chemistry B 119 (16), 5113-5123
         
        2. Developing a molecular dynamics force field for both folded and disordered protein states P Robustelli, S Piana, DE Shaw Proceedings of the National Academy of Sciences 115 (21), E4758-E4766
   
        3.  Development of a force field for the simulation of single-chain proteins and protein–protein complexes. Journal of chemical theory and computation, 16(4), pp.2494-2507. 
  
* **parameters:** All atom simulations parameters files (md.mdp,ions.mdp,minim.mdp,npt.mdp,nvt.mdp)
  * In 'ions.mdp' file coulombtype was adjusted to PME
  * md300_500K.mdp file is parameter file for simulated annealing.
  
  </br>

* **wtATF4_dimerstructure:** The wtATF(1-351) structures files including monomer, and homodimer.

</br>

* **fulllength_atf4_structures:** The wtATF4(1-351) structure files
  * "FL_ATF4(1-351)basin_high.pdb" file is wtATF4(1-351) , replica#3 convereged structure from basin
  * **atf4(123-351):** This directory has structure files related to truncated mutation of ATF4(123-351)
  * **d110a_d90a_atf4:** This directory has structure files related to double point mutation @ 90th and 110th position of wtATF4(1-351) from Aspartic acid to alanine.
  
</br>
