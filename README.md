# Awesome Empirical Software Engineering [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
A curated repository of data sets and tools that can be used for conducting evidence-based, data-driven research on software systems.
This research approach is often termed [experimental, or empirical software engineering](https://en.wikipedia.org/wiki/Experimental_software_engineering).
Many of the data sets can also be useful in research using [search-based software engineering](https://en.wikipedia.org/wiki/Search-based_software_engineering) methods.
The repository is named after the [Mining Software Repositories (MSR)](https://www.msrconf.org/) conference series.
For examples of such work see the MSR conference's [Hall of Fame](http://2016.msrconf.org/#/hall-of-fame).


- This list requires your input for its continuous improvement.
  Read the [contribution guide](contributing.md) for instructions on how
  you can contribute.
  Alternatively, you can send me an [email](mailto:dds@aueb.gr)
  if you find the process too cumbersome or confusing.
- For more awesome lists, see [awesome](https://github.com/sindresorhus/awesome).

## Contents
- [Repositories](#repositories)
- [Data Sets](#data-sets)
- [Tools](#tools)
- [Research Outlets](#research-outlets)

## Repositories

- [SIR](http://sir.unl.edu/portal/index.php) - Software-artifact infrastructure repository; Java, C, C++, and C# software together with test suites and fault data.
- [PROMISE](http://promise.site.uottawa.ca/SERepository/datasets-page.html) - About 20 datasets related to software engineering research.
- [FLOSSmole](https://flossmole.org/collection_details) - Collaborative collection and analysis of free/libre/open source project data.
- [Zenodo](http://zenodo.org/) - Software data collections in CERN's open-access repository.
  - [Software Engineering Artifacts Can Really Assist Future Tasks](http://zenodo.org/communities/seacraft)
  - [Empirical Software Engineering](https://zenodo.org/communities/empirical-software-engineering/)
  - [Mining Software Repositories](https://zenodo.org/communities/msr/)

## Data Sets

- [AndroidTimeMachine](https://androidtimemachine.github.io) - Graph-based dataset of commit history of 8,431 real-world Android apps.
- [AndroZoo](https://androzoo.uni.lu/) - Collection of Android Applications.
- [Bug Prediction Dataset](http://bug.inf.usi.ch/index.php) - Collection of models and metrics from Eclipse JDT Core, PDE UI, Equinox Framework, Lucene, Mylyn, and their histories.
- [Code Reviews](http://kin-y.github.io/miningReviewRepo/) - Code reviews of OpenStack, LibreOffice, AOSP, Qt, Eclipse.
- [CoREBench](http://www.comp.nus.edu.sg/%7Erelease/corebench/) - Collection of 70 realistically Complex Regression Errors that were systematically extracted from the repositories and bug reports of four open-source software projects: Make, Grep, Findutils, and Coreutils.
- [Defects4J](https://github.com/rjust/defects4j) - Collection of 395 reproducible bugs collected with the goal of advancing software testing research.
- [Eclipse AERI stacktraces](https://software-data.org/datasets/aeri-stacktraces) - Collection of stacktraces of Exceptions encountered by users of the Eclipse IDE, as retrieved by the AERI reporting system..
- [Enron Spreadsheets and Emails](https://figshare.com/articles/Enron_Spreadsheets_and_Emails/1221767) - All the spreadsheets and emails used in the paper 'Enron's Spreadsheets and Related Emails: A Dataset and Analysis'.
- [Findbugs-maven](https://github.com/istlab/maven_bug_catalog) - Set of FindBugs reports for the Java projects of the [Maven repository](https://maven.apache.org).
- [GHTorrent](http://ghtorrent.org/) - Scalable, queriable, offline mirror of data offered through the GitHub REST API.
- [GitHub on Google BigQuery](https://cloud.google.com/bigquery/public-data/github) - GitHub data accessible through Google's BigQuery platform.
- [KaVE](http://www.kave.cc/datasets) - Developer tool interaction data.
- [Maven metrics](https://github.com/bkarak/data_msr2015) - Collection of software complexity & sizing metrics for the [Maven Repository](https://maven.apache.org).
- [Maven Dependency Graph](https://zenodo.org/record/1489120) - Snapshot of the whole Maven Central taken on September 6, 2018, stored in a graph database.
- [mzdata](https://github.com/jxshin/mzdata) - Multi-extract and multi-level dataset of Mozilla issue tracking history.
- [npm-miner](https://github.com/AuthEceSoftEng/msr-2018-npm-miner) - The dataset contains the analysis results of 5 open source software quality tools eslint, escomplex, nsp, jsinspect and sonarjs for 2000 popular (in terms of stars and downloads) npm packages.
- [OCL Expressions on GitHub](https://github.com/tue-mdse/ocl-dataset) - Data set of 9188 OCL expressions originating from 504 EMF meta-models in 245 systematically selected GitHub repositories.
- [RepoReapers Data Set](https://reporeapers.github.io) - Data set containing a collection of _engineered software projects_ from GHTorrent.
- [SOTorrent](http://sotorrent.org) - Data set based on the official Stack Overflow dump, providing acccess to the version history of Stack Overflow code snippets and links to/from Stack Overflow posts.
- [STAMINA](http://stamina.chefbe.net/download) - (STAte Machine INference Approaches) data are used to benchmark techniques for learning deterministic finite state machines (FSMs).
- [Stack Exchange](https://archive.org/details/stackexchange) - Anonymized dump of all user-contributed content on the Stack Exchange network.
- [TravisTorrent](http://travistorrent.testroots.org) - Provides free and easy-to-use Traivs CI build analyses.
- [Ultimate Debian Database (UDD)](https://wiki.debian.org/UltimateDebianDatabase) - Data about various aspects of Debian (e.g. packages, bugs, mainteners) in the same SQL database.
- [Unix history](https://github.com/dspinellis/unix-history-repo) - Git repository with 46 years of Unix history evolution.

## Tools

- [Boa](http://boa.cs.iastate.edu/) - Domain-specific language and infrastructure that eases mining software repositories.
- [ckjm](http://www.spinellis.gr/sw/ckjm/) - Chidamber and Kemerer Java Metrics.
- [Coming](https://github.com/SpoonLabs/coming/) - A Java framework for analyzing code changes and mining instances of change patterns from Git repositories.
- [DbDeo](https://github.com/tushartushar/DbDeo) - Extract embedded SQL statements and detect database schema smells.
- [Designite](http://www.designite-tools.com) - Compute source code metrics and detect a variety of implementation, design, and architecture smells for C#.
- [DesigniteJava](https://github.com/tushartushar/DesigniteJava) - Compute source code metrics and detect a variety of implementation and design smells for Java.
- [Diggit](https://github.com/jrfaller/diggit) - Agile Ruby Tool to analyze Git repositories.
- [GrimoireLab](http://grimoirelab.github.io/) - Free/Libre/Open Source tools for Software Development Analytics.
- [MetricMiner](http://www.github.com/mauricioaniche/metricminer2) - Lean Java DSL to mine and extract data (e.g. commits, developers, modifications, diffs) from Git and SVN repositories.
- [Maven-miner](https://github.com/diverse-project/maven-miner) - Java tools and infrastructure to resolve the whole Maven dependency graph, hosted in Maven Central, in the form of a [Neo4j](https://neo4j.com/) Graph.
- [Puppeteer](https://github.com/tushartushar/Puppeteer) - Detect configuration smells in Puppet code.
- [PyDriller](https://github.com/ishepard/pydriller) - Python Framework to analyse Git repositories.
- [qmcalc](https://github.com/dspinellis/cqmetrics) - Calculate quality metrics from C source code.
- [reaper](https://github.com/RepoReapers/reaper) - Python tool to compute a score for a repository from GHTorrent. The score quantifies the extent to which the project contained within the repository is _engineered_.
- [VulData7](https://github.com/electricalwind/data7) - Java framework enabling the automated collection of commits fixing vulnerabilities that are reported in NVD (links NVD with Git).

## Research Outlets
- Outlets exclusively devoted to empirical software engineering research
  - [Empirical Software Engineering journal](https://link.springer.com/journal/10664)
  - [MSR: Mining Software Repositories conference](https://www.msrconf.org/)
  - [PROMISE: Predictive Models and Data Analytics in Software Engineering conference](http://promisedata.org/)
- Outlets that publish empirical software engineering research
  - [ACM Transactions on Software Engineering and Methodology (TOSEM)](https://dl.acm.org/citation.cfm?id=J790)
  - [ESEC/FSE: ACM Joint European Software Engineering Conference and Symposium on the Foundations of Software Engineering](https://www.esec-fse.org/)
  - [ICSE: International Conference on Software Engineering](http://www.icse-conferences.org/)
  - [IEEE Software magazine](https://publications.computer.org/software-magazine/)
  - [IEEE Transactions on Software Engineering](https://www.computer.org/csdl/journal/ts)
  - [Journal of Systems and Software](https://www.journals.elsevier.com/journal-of-systems-and-software)
  - [SANER: IEEE International Conference on Software Analysis, Evolution and Reengineering](https://ieeexplore.ieee.org/xpl/conhome.jsp?punumber=1000695)


## License

[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Diomidis Spinellis](http://www.spinellis.gr) has waived all copyright and related or neighboring rights to this work.
