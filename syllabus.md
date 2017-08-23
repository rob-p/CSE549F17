---
layout: post
title: Syllabus
published: true
---
Welcome to Computational Biology (CSE 549). Here you'll find an overview of the course — the material I expect we'll cover, the breakdown of course assignments and credit, and the course policies.

## Course Content

**Textbook(s)**: The officially listed textbooks for this course are "Bioinformatics Algorithms: An Active Learning Approach" [Volume I](https://www.amazon.com/Bioinformatics-Algorithms-Active-Learning-Approach/dp/0990374610) and [Volume II](https://www.amazon.com/Bioinformatics-Algorithms-Active-Learning-Approach/dp/0990374629/ref=pd_sim_14_1?ie=UTF8&psc=1&refRID=40X4TFRTNNVP26HCPYX0). The lectures and slides will introduce the topics and cover the majority of the information you'll be expected to know. Further resources, where relevant, will be provided via links on this website accompanying the slides or lecture notes. However, you should use these textbooks as a resource when you feel you need more information about a particular topic or when you wish to learn the material at a different pace than we cover in the course.  There are other (non-required) textbooks that I personally recommend as references:

- [Genome Scale Algorithm Design](http://www.cs.helsinki.fi/group/gsa/book/) (Mäkinen, Belazzougui, Cunial, Tomescu 2015)
- [Biological Sequence Analysis](http://www.amazon.com/Biological-Sequence-Analysis-Probabilistic-Proteins/dp/0521629713) (Durbin, Eddy, Krogh, Mitchinson 1998)

If, you're from a discipline where you've not had a formal algorithms course, I find 

- [Algorithms](http://beust.com/algorithms.pdf) (Dasgupta, Papadimitriou, and Vazirani 2006) to be a nice introduction to the basics. 
 
I also recommend 

- [Algorithm Design](http://www.amazon.com/Algorithm-Design-Jon-Kleinberg/dp/0321295358) (Kleinberg and Tardos 2006) 
 
and, of course, 

- [The Algorithm Design Manual](http://www.amazon.com/gp/product/1848000693/ref=pd_lpo_sbs_dp_ss_3?pf_rd_p=1944687742&pf_rd_s=lpo-top-stripe-1&pf_rd_t=201&pf_rd_i=0321295358&pf_rd_m=ATVPDKIKX0DER&pf_rd_r=02TJC7H7CDMT55WH5X9V) (Skiena 2008).

We will cover the basic required molecular Biology in the course. However if you're not familiar with basic molecular Biology, there are some useful resources worth reading:

- [Molecular Biology of the Cell](http://www.ncbi.nlm.nih.gov/books/bv.fcgi?call=bv.View..ShowTOC&rid=mboc4.TOC&depth=2), by Bruce Alberts, Alexander Johnson, Julian Lewis, Martin Raff, Keith Roberts, and Peter Walter. Garland Publishing, 2002. — This is a great free resource.

- [Molecular Biology](http://www.amazon.com/Molecular-Biology-Second-Edition-David/dp/0123785944) (Clark and Pazdernik 2012)

**Expectations**: Since this is a computational Biology course, you will be expected to become familiar with the relevant Biology — it is an important and inextricable part of the material, and the underlying Biology provides motivation for the computational problems we will tackle.

**Course Objectives**: The main objective of this course will be to provide a broad overview of the major areas of Bioinformatics and Computational Biology (B/CB). Our perspective will be a computational and algorithmic one, though we will take the time to understand the necessary Biology and motivation for the problems we discuss. We will touch upon many areas of B/CB, including phylogenetics, genome structure and Biological network analysis. However, there will be a significant concentration on genomics and related problems such as high-throughput read alignment, gene finding, genome assembly and transcriptome assembly and analysis. At the end of this course, you should have a good understanding of the types of problems people work on in B/CB, and a fairly in-depth knowledge of the computational tools and techniques used to address some foundational problems in the field.  A tentative list of topics we will cover (depending on how quickly we move) is:

  * Optimal sequence alignment (global, local, and glocal alignment — with constant & affine gap penalties
  * Algorithms and data structures for efficient text indexing and *exact* search
  * Heuristics for read *alignment* and *mapping* — mapping DNA-seq and RNA-seq reads
  * Genome assembly — k-mers, De Brujin graph construction and representation, long-read technology and read-overlap graph assembly
  * Motif finding via Gibbs sampling
  * Gene finding — statistical models for *ab initio* and evidence-guided prediction of genes
  * RNA-seq and transcriptomics — transcript assembly, abundance estimation and differential expression testing
  * Phylogenetics — The small and large phylogeny problem; parsimony, maximum likelihood and Bayesian methods

## Course Policy

**Coursework and grading**: The coursework will consist of two exams, a midterm (whose tentative date is Tues, October 11) and a final (on the University-scheduled date). In addition there will be a few homework assignments (some small programming assignments, and one or two written homeworks that will require you to devise / explain an algorithm, or prove some properly about an algorithm or data structure that we cover in class) and a final course project. The final project can be selected from a list of projects that will be distributed in a few weeks. The project will be done in teams of 3 - 4 students (a team of 2 is OK, but no solo projects and **no teams > 4 students**). For the final project, there will be a brief (7 min) presentation by each group, a deliverable as runnable code, and a short (4-5 page) research-style paper describing the work you've done. The breakdown of weights for these different assignments will be as follows:

- Midterm — 30%
- Final — 30%
- Final Project — 20%
- Homeworks — 20%

**Regrade policy**: All requests to re-grade, re-check, or re-mark an assignment or exam question **must be made in writing**. When the assignment is re-graded, it will be re-checked in its entirety. This means that *it is possible to lose points on other problems if they were graded incorrectly or too leniently the first time*. Therefore, I urge you to thoroughly consider each regrade request you make.

**Excused Absences**: If you miss a class for a medical or health-related reason, please provide me with a record of this in writing or via e-mail (I do not need to know the specifics, just the date of your absence and that it was for a medical or health reason). If, for a health-related or medical reason, you will miss two or more consecutive classes, or will miss class on a recurring basis, or were unable to meet a particular academic obligation of this course, I will require a written note from the Student Health Service or a healthcare provider documenting the range of dates for which you were unable to meet your academic obligations. This note need not contain any diagnostic information. If you will miss any classes or scheduled exams as a result of religious observances, you must submit this information to me, in writing, within the first two weeks of the semester to make necessary accommodations to complete the work that will be missed.

**Final Grades**: The grade you receive in this class will reflect, as much as possible, the degree to which you have mastered the necessary material. How much somebody “needs” an ‘A’ will have no bearing on whether or not (s)he receives an ‘A’, other than how this need or desire is reflected in the work that (s)he does. I want everyone to do well in this course, and will make every reasonable effort to help you understand the material as well as possible. However, barring errors in the grading of assignments, the grades you receive at the end of the semester are final, and I will not alter them for personal or non-academic reasons, *so please do not ask me to*!

**Academic integrity**: [From the University’s Academic Integrity Syllabus Statement](http://www.stonybrook.edu/commcms/academic_integrity/syllstate.html):

> Each student must pursue his or her academic goals honestly and be personally accountable for all submitted work. Representing another person’s work as your own is always wrong. Any suspected instance of academic dishonesty will be reported to the Academic Judiciary. For more comprehensive information on academic integrity, including categories of academic dishonesty, please refer to the academic judiciary website at www.stonybrook.edu/academicintegrity.

Academic integrity is a very serious issue. Any assignment, project or exam you complete in this course is expected to be your own work. If you are allowed to discuss the details of or work together on an assignment, this will be made explicit. Otherwise, you are expected to complete the work yourself. *Plagarism is not just the outright copying of content*. If you paraphrase someone else's thoughts, words, or ideas and you don't cite your source, this constitues plagraism (i.e. this is just as bad as copying someone's answer on an exam or code on a homework). It is always much better to turn in an incorrect or incomplete assignment representing your own efforts than to attempt to pass off the work of another as your own. I have a lot of tolerance for those who are making a significant effort but may be having trouble understanding a particular concept or completing a certain assignment. However, there will be no tolerance of academic dishonesty. **If you are academically dishonest in this course, you will recieve a grade of F, and you will be reported to the department's academic integrity committee**.

**Learning disabilities**: If you have a physical, psychological, medical or learning disability that may impact your course work, please contact Disability Support Services, ECC (Educational Communications Center) Building, room 128, (631) 632-6748. They will determine with you what accommodations, if any, are necessary and appropriate. All information and documentation is confidential.
