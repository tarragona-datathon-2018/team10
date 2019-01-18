# TGN_Datathon2018
Research for MIMIC-III(1)(making locally in progress), eICU(2), and icu23(not now, future) medical databases from Physionet(0) Colaborative Research Database(1).

##TARRAGONA DATATHON, November 2018, team_10 activities
### Impact on fluid overload on the evolution of patients with septic shock

* Marianna Polini: Data Scientist / SQL-Databases, 
* Christian Villavicencio: Clinician, 
* Eva Machado: Clinician, 
* Raquel Carbonell: Clinician, 
* Diana Gil: Clinician, 
* Laia Labad: Clinician, 
* Santiago Frias: Data Scientist / Statistics-Models




### According to the attached document, the concept blocks are structured and the works to be carried out are recursively displayed
![alt text](https://github.com/tarragona-datathon-2018/team10/blob/master/Project01.png)
### Example of preliminary analysis: ScatterPlot of id patient numbers (x axis) to timestamp events (y axis)
![alt text](https://github.com/tarragona-datathon-2018/team10/blob/master/PatientShockSepticMore3d.png)

Created a Bare Metal Plattform to continue research locally:

* A Laptop as a prototype for Inference   
[![alt text](https://www.passmark.com/baselines/V9/images/113731726464.png)](https://www.passmark.com/baselines/V9/display.php?id=113731726464)
* A Nvidia Development Platform Jetson TX2 to train model[![alt text](https://developer.nvidia.com/sites/default/files/akamai/embedded/images/jetsontx2/TX2_Module_170203_0017_TRANSP_2000px.png)](https://developer.nvidia.com/embedded/buy/jetson-tx2-devkit)

Created a secured and certified system undel Debian Linux, with lvm2 crypted storage, Certificated&Registered data access. Limited quota&audited downloads. Frontend on Jupyter NB connected on csv's and MariaDB SQL columnar database to improve efficiency.
 First of goals for this project is guarantee as much as possible the privacy and confidentiality of the process information with which you work, and notify any data association that may be able to skip this restriction. At this time it has been assumed.
 
 Activities Development process detailed on ![StatDev.md](https://github.com/tarragona-datathon-2018/team10/blob/master/StatDev.md)
 
 References:
 
(0) Physionet Network:
Goldberger AL, Amaral LAN, Glass L, Hausdorff JM, Ivanov PCh, Mark RG, Mietus JE, Moody GB, Peng C-K, Stanley HE. PhysioBank, PhysioToolkit, and PhysioNet: Components of a New Research Resource for Complex Physiologic Signals. Circulation 101(23):e215-e220 [Circulation Electronic Pages; http://circ.ahajournals.org/content/101/23/e215]; 2000 (June 13).

(1)  MIMIC-III Clinical Database is 1.4 (4 September 2016; 46,520 subjects). For further information, please visit the MIMIC website: http://mimic.physionet.org/
MIMIC-III, a freely accessible critical care database. Johnson AEW, Pollard TJ, Shen L, Lehman L, Feng M, Ghassemi M, Moody B, Szolovits P, Celi LA, and Mark RG. Scientific Data (2016). (DOI: 10.1038/sdata.2016.35). Available from: http://www.nature.com/articles/sdata201635
 
(2) eICU Collaborative Research Database:
(eICU-CRD) is v2.0 (17 May 2018). For further information, please visit the eICU-CRD website: http://eicu-crd.mit.edu/
Pollard TJ, Johnson AEW, Raffa JD, Celi LA, Mark RG, Badawi O.The eICU Collaborative Research Database, a freely available multi-center database for critical care research. Scientific Data, 5:180178, Sept. 2018. (doi:10.1038/sdata.2018.178)
