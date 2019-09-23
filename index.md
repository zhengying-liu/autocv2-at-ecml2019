---
layout: default
---

# Description

Despite recent successes of deep learning and other machine learning techniques, practical experience and expertise is still required to select models and/or choose hyper-parameters when applying techniques to new datasets. This problem is drawing increasing interest, yielding progress towards fully automated solutions. **AutoCV2 challenge**, among [other AutoDL challenges](https://autodl.chalearn.org/), aims to search for such solutions, without human intervention whatsoever. More specifically, participants' machine learning code is trained and tested on image or video classification tasks one has never seen before, with _time_ and _memory_ limitations. All problems are multi-label classification problems, coming from various domains including medical imaging, satellite imaging, object recognition, character recognition, face recognition, human action classification etc.

In this workshop, we'll present the challenge results. Challenge winners are
invited to introduce their approaches. This is also the occasion to have a brief
award ceremony. The winners in AutoCV2 challenge are:
- 1st place ($2000 prize): **kakaobrain** ([GitHub repo](https://github.com/kakaobrain/autoclint))
- 2nd place ($1500 prize): **tanglang** ([GitHub repo](https://github.com/tanglang96/AutoCV2))
- 3rd place ($500 prize): **kvr** ([GitHub repo](https://github.com/kvr777/autodl_cv2))

Top submissions used approaches such as
- [Fast AutoAugment](https://github.com/kakaobrain/autoclint)
- [MobileNet](https://arxiv.org/abs/1704.04861)
- [ResNet](https://arxiv.org/abs/1512.03385)

These approaches turn out to have good **any-time learning**
(see [challenge design](https://hal.archives-ouvertes.fr/hal-02265053))
performance. And interestingly, the final performance is,
for the most of the time, NOT compromised. This means that approaches have
good any-time performance globally have good final performance.

This workshop is collocated with ECML PKDD 2019. For more details,
please refer to:
- [Official website of ECML PKDD 2019](http://ecmlpkdd2019.org)
- [ECML Discovery Challenges](http://ecmlpkdd2019.org/submissions/discovery/)
- [Timetable](http://ecmlpkdd2019.org/programme/timetable/)

# Call for Abstracts
Challenge winners/top-rankers are invited to submit a 2-page extended abstract describing
their approach used in AutoCV2 Challenge.

Papers must be written in English and formatted according to the Springer LNCS
guidelines. Author instructions, style files and the copyright form can be
downloaded [here](http://www.springer.com/gp/computer-science/lncs/conference-proceedings-guidelines).

Submission via: [autodl@chalearn.org](mailto:autodl@chalearn.org)

# Important Dates
* Abstract Submission Deadline: 13 September, 2019
* Workshop: 20 September, 2019

# Venue
Room: 2.007

Building Z6, Hubland Campus, University of Würzburg

Z6, Am Hubland, 97074 Würzburg

# Schedule

| Slot               |           Event           |
|:------------------ |:------------------------- |
| 14:00-14:30      | Welcome and general presentation of the AutoCV2 challenge and AutoDL challenges: design and results. Issue award certificates to winners. Take photos. |
| 14:30-15:00      | Keynote: **Open Source AutoML Benchmarking: towards an AutoML Gym**, Joaquin Vanschoren. |
| 15:00-15:10      | Invited talk 1: **Meta Neural Architecture Search**, Jinlin Wang, _ether_   |
| 15:10-15:20      | Invited talk 2: **Efficient Deep Representation Optimization for Cross-Modal Automated Deep Learning under Time and Space Constraints**, Mohammadreza Amirian, _team_zhaw_, [extended abstract](https://drive.google.com/file/d/1OaZa-8AQefaY00wLrkp5pkhmdoyER7bY/view?usp=sharing), [slides](https://drive.google.com/file/d/1bHvej3C9WRvn3G6Rftfi9DsrJfGwBXMm/view?usp=sharing)  |
| 15:20-15:30      | Invited talk 3: **My Way to Build Fast, Scalable and Generalized Computer Vision Model**, Kirill Romanov, _kvr_, [slides](https://drive.google.com/file/d/1bHvej3C9WRvn3G6Rftfi9DsrJfGwBXMm/view?usp=sharing)  |
| 15:30-15:45      | Recorded Presentation: **Multinomial Distribution Learning for Effective Neural Architecture Search**, Lang Tang, _tanglang_, [video](https://drive.google.com/file/d/1YJn60cGaJVs0hbpIurA_3BWm-bpmMl6O/view?usp=sharing) |
| 15:45-16:00      | Invited talk 4: **Fast AutoAugment**, Curtis Kim, _kakaobrain_  |

# Keynote Speaker
<img src="https://joaquinvanschoren.github.io/home/images/profilepic.jpg" alt="Joaquin Vanschoren" style="width:220px;">

[<span style="font-size:1.5em;">Joaquin Vanschoren</span>](https://joaquinvanschoren.github.io/home/)

Assistant professor of machine learning at TU/e (Eindhoven University of Technology)

Founder of [OpenML.org](https://www.openml.org/)

**Talk title**: Open Source AutoML Benchmarking: towards an AutoML Gym

**Abstract**:
In recent years, an active field of research has developed around automated machine learning (AutoML). Unfortunately, comparing different AutoML systems is hard and often done incorrectly. First, we currently lack standardized, easily-accessible, and challenging benchmarking suites of tasks. This often results in suboptimal shortcuts in study designs, exacerbated by a focus on competition rather than understanding, which makes papers very hard to compare and reproduce. Second, we lack a standardized environment for experimentation and publications. Subtle differences in the problem definition can drastically alter a task’s difficulty, which makes it difficult to reproduce published research and compare results from different papers. Third, we lack a meta-learning environment, a global memory where AutoML systems can easily access meta-data from previous ML experiments and can upload their own. We propose to build a global, open source environment for training and evaluating AutoML systems - an **AutoML Gym** - that addresses these issues.

# Invited Speakers

* **Jinlin Wang** (fuzhi.ai), from team _ether_ (5th place)

* **Mohammadreza Amirian** (Zurich University of Applied Sciences), from team _team_zhaw_ (3rd place in feedback phase)

* **Kirill Romanov**, from team _kvr_ (3rd place)

* **Lang Tang** (Xiamen University) from team _tanglang_ (2nd place)

* **Curtis Kim** (Kakao Brain) (to be confirmed) from team _kakaobrain_ (1st place, also 1st place in AutoCV Challenge)

# Organizers
Workshop chairs:
* Hugo Jair Escalante (IANOE, Mexico and ChaLearn, USA)
* Zhengying Liu (U. Paris-Saclay; UPSud, France)

Main organizers:
* Olivier Bousquet (Google, Switzerland)
* André Elisseef (Google, Switzerland)
* Isabelle Guyon (U. Paris-Saclay; UPSud/INRIA, France and ChaLearn, USA)
* Zhengying Liu (U. Paris-Saclay; UPSud, France)
* Wei-Wei Tu (4paradigm, China)

Other contributors to the organization, starting kit, and datasets, include:
* Stephane Ayache (AMU, France)
* Hubert Jacob Banville (INRIA, France)
* Mahsa Behzadi (Google, Switzerland)
* Kristin Bennett (RPI, New York, USA)
* Hugo Jair Escalante (IANOE, Mexico and ChaLearn, USA)
* Sergio Escalera (U. Barcelona, Spain and ChaLearn, USA)
* Gavin Cawley (U. East Anglia, UK)
* Baiyu Chen (UC Berkeley, USA)
* Albert Clapes i Sintes (U. Barcelona, Spain)
* Bram van Ginneken (Radboud U. Nijmegen, The Netherlands)
* Alexandre Gramfort (U. Paris-Saclay; INRIA, France)
* Yi-Qi Hu (4paradigm, China)
* Julio Jacques Jr. (U. Barcelona, Spain)
* Meysam Madani (U. Barcelona, Spain)
* Tatiana Merkulova (Google, Switzerland)
* Adrien Pavao (U. Paris-Saclay; INRIA, France and ChaLearn, USA)
* Shangeth Rajaa (BITS Pilani, India)
* Herilalaina Rakotoarison (U. Paris-Saclay, INRIA, France)
* Mehreen Saeed (FAST Nat. U. Lahore, Pakistan)
* Marc Schoenauer (U. Paris-Saclay, INRIA, France)
* Michele Sebag (U. Paris-Saclay; CNRS, France)
* Danny Silver (Acadia University, Canada)
* Lisheng Sun (U. Paris-Saclay; UPSud, France)
* Sebastien Treger (La Pallaisse, France)
* Fengfu Li (4paradigm, China)
* Lichuan Xiang (4paradigm, China)
* Jun Wan (Chinese Academy of Sciences, China)
* Mengshuo Wang (4paradigm, China)
* Jingsong Wang (4paradigm, China)
* Ju Xu (4paradigm, China)
* Zhen Xu (Ecole Polytechnique and U. Paris-Saclay; INRIA, France)
