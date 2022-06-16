# FoRMA'22: The First Workshop on the Future of MPI RMA

## Welcome to FoRMA'22

MPI Remote Memory Access (RMA) has been part of the MPI standard since MPI 2.0, with significant extensions made in MPI 3.0. With hardware technologies and the application space constantly evolving, it is time to reflect on the current state of affairs and to gather input for future directions of the RMA interface.

The goal of the FoRMA'22 workshop is to bring together users and implementors of MPI RMA as well as system vendors to discuss the current state of MPI RMA and exchange ideas about its future. While the MPI RMA (and related PGAS interfaces) have been the subject plenty of research work, only minor changes have been made in the past decade. The goal of this workshop is to bring together four important groups relevant for MPI RMA:

1) Users of MPI RMA developing real world applications: experiences, successes, and challenges;
2) Implementors of MPI RMA: challenges in efficienly implementing the current semantics of MPI RMA and ideas for simplifications and extensions;
3) Hardware vendors: input on future directions of network hardware and how to adapt MPI RMA to better map onto current and future hardware;
4) Related PGAS models (e.g., OpenSHMEM): lessons learned over the past decade(s) in designing alternative PGAS abstractions.

### Format

The FoRMA'22 workshop will comprise a range of invited speakers covering the above groups. Our stated goal is to include researchers and practitioners from both within and outside the usual MPI RMA research circles. We also plan to call for short and medium talks for users to talk about the challenges they faced and successes they achieved in using MPI RMA.

The workshop is meant to be held rather informally to keep the barriers for participation low. Given the ongoing pandemic situation and the uncertainties that come with it, we plan to hold the workshop virtually. 

### Date and Time

June 15 & 16, 2022, 8am to 1pm CDT.

### Registration

To register for the workshop (and receive the access link) please use the [registration site](https://tennessee.zoom.us/meeting/register/tJ0qduChrDgsGNdEG3MQeLB-DH3lZ6r-DZww). Participation is free and registration is meant to protect us from the bots.

### Program

Tentative program, minor changes and additions possible. All times are CDT. For most we plan 30 minutes per talk + 10 minute discussion.

#### June 15
| Time &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;| Speaker &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; | Title |
|:----------- |:-----|:---------------|
| 8:00 - 8:10 | Joseph Schuchart | Welcome ([Slides](https://github.com/mpiwg-rma/forma22/files/8922374/FoRMA22_intro.pdf)) |
| 8:10 - 8:50 | Bill Gropp | *MPI RMA: Is It Time To Start Over?* ([Slides](https://github.com/mpiwg-rma/forma22/files/8922399/mpi-rma-vision.pdf)) |
| 8:50 - 9:35 | Jeff Hammond (Nvidia) | *Experiences with MPI RMA as a foundational communication abstraction for one-sided programming models* ([Slides](https://github.com/mpiwg-rma/forma22/files/8922380/2022.June.Hammond.MPI.RMA-1.pdf)) |
| 9:35 - 10:15 | Marc Sergent (Atos Bull) | *MPI-RMA at Bull* ([Slides](https://github.com/mpiwg-rma/forma22/files/8922409/FORMA22_MPI-RMA-Bull.pdf)) |
| 10:15 - 10:30 | | Break |
| 10:30 - 11:10 | Ioan Hadade (ECMWF) | *Experiences and opportunities for one-sided communication in the ECMWF weather forecasting model* ([Slides](https://github.com/mpiwg-rma/forma22/files/8922383/ecmwf_ifs_one_sided.pdf)) |
| 11:10 - 11:50 | Marc Snir (UIUC) | *Task Asynchronous Programming Models and One-Sided Communication.* |
| 11:50 - 12:30 | Jim Dinan (NVIDIA) | *NVSHMEM: CUDA-Integrated Communication for NVIDIA GPUs* ([Slides](https://github.com/mpiwg-rma/forma22/files/8922387/NVSHMEM.-.FORMA._22.pdf)) |

#### June 16
| Time &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp;| Speaker &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; &nbsp; | Title |
|:----------- |:-----|:---------------|
| 8:00 - 8:40 | Richard Graham (Nvidia) | *Perspective on MPI one-sided application support*      |
| 8:40 - 9:20 | Naveen Ravi (HPE) | *Early Experience in Supporting One-sided Communications on Slingshot 11* |
| 9:20 - 10:00 | Maria Garzaran (Intel) | *Should we enable MPI RMA calls from the GPU?* |
| 10:00 - 10:15 | | Break |
| 10:15 - 11:00 | Nils Imhoff & Christian Simmendinger (HPE) | *GASPI & Notified Communication in MPI RMA* ([Slides](https://github.com/mpiwg-rma/forma22/files/8922393/gaspi_brief_overview.pdf)) |
| 11:00 - 11:40 | Yanfei Guo (ANL) | *Lessons Learned From OSHMPI* |
| 11:40 - 12:00 | User Short Talks: Chris Brady (University of Warwick) | *Experiences adding MPI RMA to the DFT code ONETEP* |
| 12:00 - 12:15 | User Short Talks: Sayan Ghosh (PNNL) | *Using MPI RMA in Graph Analytics* |
| 12:15 - 13:00 | Jim Dinan, Torsten Hoefler, Keith Underwood, Jeff Hammond, Bill Gropp | *Panel Discussion* ([Slides](https://github.com/mpiwg-rma/forma22/files/8922405/FORMA.22.Panel.pdf)) |


### Proceedings

There will be no official proceedings with papers from individual authors. However, we plan to release a combined whitepaper summarizing the outcomes of the workshop.

### Recordings

The talks at the workshop will be recorded (via Zoom) and made available afterwards.

### Organizers

- Joseph Schuchart (University of Tennessee, Knoxville)
- James Dinan (Nvidia)
- Bill Gropp (University of Illinois Urbana Champaign)
