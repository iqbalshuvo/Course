# DevOps: CSC 519
-------------------------

Modern software development organizations require entire teams of DevOps to automate  and maintain software engineering processes and infrastructure vital to the organization. In this course, you will gain practical exposure to the skills, tools, and knowledge needed in automating software engineering processes and infrastructure. 
Students will have the chance to build new or extend existing software engineering tools and design a DevOps pipeline.

Past versions:
* [Fall 2017](https://github.com/CSC-DevOps/Course/tree/Fall2017)
* [Spring 2017](https://github.com/CSC-DevOps/Course/tree/Spring2017)
* [Fall 2016](https://github.com/CSC-DevOps/Course/tree/Fall2016)
* [Spring 2015 ](https://github.com/CSC-DevOps/Course/tree/Spring2015)
* [Fall 2015 ](https://github.com/CSC-DevOps/Course/tree/Fall2015)

## Course Overview

In the course, a mixture of traditional lectures with activities and in-class workshops will be used.  During lectures, we will cover core concepts related to a topic. During the in-class workshops, we will perform sample exercises with relevant tools that reinforce lecture material.  Evaluation will be based on tech talks, homework assignments, workshop attendance, and final project.

After the course, students are able to:

* Programmatically **provision** images.
* Automatically apply **configuration management** to production environments.
* Automatically create and maintain **build** environments.
* Maintain test suites and measure **testing quality** and coverage.
* Automatically **generate new tests**, using feedback-directed random testing, fuzzing, and data-flow analysis.
* Programmatically measure **code quality** via static and dynamic code analysis.
* Understand components of **infrastructure**.
* Remotely regulate behavior of deployed software via **feature flags** and configuration servers.
* Apply advanced strategies for **deployment** of software.
* Monitor and analyze **telemetry** data.
* Implement **resilience testing** on production environments (e.g., Chaos Monkey).

### Project

The primary objective of the course will be to allow students to gain experience in incrementally building a continous delivery pipeline from scratch.  Throughout the semester, students are expected to complete a component of the pipeline by each milestone deadline.

##### Milestones

Details on requirements for milestones will be released throughout the course.  A student's pipeline should demonstrate the following components by the milestone deadline:

* CM
* BUILD+TEST+ANALYSIS
* DEPLOY
* SPECIAL

## TA

Shrikant Shete, Office Hours: Thursday 3:15-4:15pm


## Schedule and Topics - Spring 2018

The following schedule is subject to change.

| Class    | Topics                           |  Resources | Assignments       |
|----------|----------------------------------|------------| ----------------  |
| Jan 9    | [Computing Environments](https://github.com/chrisparnin/ComputingEnvironmentsWorkshop) |            |                   |
| Jan 11   | [Pipeline Basics](Workshops/PipelineBasics.md)| | [HW0](HW/HW0-Pipelines.md)|
| Jan 16   | [Core Concepts](http://tiny.cc/CSC-DevOpsCore)|  [Adages](https://github.com/CSC-DevOps/Course/blob/master/Readings/AdagesI.pdf)        |
| Jan 18   | Snow Day                         |            |                   |
| Jan 23   | [Configuration Management](https://docs.google.com/presentation/d/1PO_QTieMkRvW9MDEIMVS0dD5bk50fK5fvSgj5zNyPfw/edit#slide=id.g117c3bc2e1_0_0)         |            |  [HW1](HW/HW1-C.md)              |
| Jan 25   | [Ansible](https://github.com/CSC-DevOps/CM#configuration-management-workshop)|            |                   |
| Jan 30   | ...continued                     |            |                   |
| Feb 1    | [Provisioning workshop](https://github.ncsu.edu/CSC-DevOps-Spring2015/ServersWorkshop)            |            |[HW1 - P2](HW/HW1-A.md)|
| Feb 6    | [Build](https://docs.google.com/presentation/d/1PeI-RbsisPtC8tbKMgtB3IDlffLjE6obQkp-tL0Cmsw/edit#slide=id.p)                            |            |[CM+Build Milestone](Project/CM.md)|
| Feb 8    | [Build server workshop](https://github.com/CSC-DevOps/Course/blob/master/Workshops/Build.md)            |            |                   |
| Feb 13   | [Test Management](https://docs.google.com/presentation/d/1Wv149dt56DAixTn5BqdyHwVxBWyHU1pk5ohL7jlVAWs/edit#slide=id.p)                  |            |                   |
| Feb 15   | [Suites](https://github.com/CSC-DevOps/TestSuites)/[Fuzzing](https://github.com/CSC-DevOps/Fuzzing)                   |            |                   |
| Feb 20   | [Analysis](https://docs.google.com/presentation/d/1EkfcbwXko9gvtel0t4GD_cpE4me-OAIwdYt0p_OAeIs/edit#slide=id.p)                         |            |  [Test+Analysis Milestone](Project/BuildTestAnalysis.md)                    |
| Feb 22   | [Test Generation Workshop](https://github.com/CSC-DevOps/TestGeneration)                  |            |  [HW2](HW/HW2.md)       |
| Feb 27   | [Deploy Strategies](https://docs.google.com/presentation/d/1J3oDEPSGzDGa0B41Ppe8yA02tYicSgstVXHU5mGxU5w/edit#slide=id.g1da8fd6af9_0_0)                |            |                   |
| Mar 1    | [Deploy](https://github.com/CSC-DevOps/Deployment)                           |            |                   |
| Mar 6    | SPRING                           |            |                   |
| Mar 8    | BREAK                            |            |                   |
| Mar 13   | [Operation Concepts](https://docs.google.com/presentation/d/19TYz-XK5ou3mZP9I5a_Hp44ZQ-MsLK27yQyUaR1D8tc/edit#slide=id.g3527d62d8d_0_0)               |            |                   |
| Mar 15   | [Redis](https://github.com/CSC-DevOps/Queues)                            |            |                   |
| Mar 20   | Michael DeHaan, ansible creator  |            |   [DEPLOY+INFRA Milestone](Project/M3.md)                |
| Mar 22   | [Tech Talks](TechTalks.md)                       | [Kubernetes](https://github.ncsu.edu/khchoksi/Kubernetes-Tech-Talk), [Coveralls](https://github.ncsu.edu/sssaha2/CoverallsDemo), [TravisCi](https://github.com/rjain9/TravisCI), [Monit](Monit)           |                   |
| Mar 27   | [Monitoring/Analysis](https://docs.google.com/presentation/d/1swei7oeXWZGnXe9gC1jlh4Gd1h9Ri6I6x2kTgKr1BVw/edit#slide=id.p)              |            |                   |
| Mar 29   | [Monitoring Workshop](https://github.com/CSC-DevOps/Monitoring)                                 |            |                   |
| Apr 3    | [Tech Talks](TechTalks.md)                       | [Chef](https://github.ncsu.edu/dguttik/Chef-repo), [SonarQube](https://github.ncsu.edu/rcoutin/SonarQube), [Eslint](https://github.ncsu.edu/davitond/Eslint), [Lambda](https://github.com/AnkurSaxena135/AWS-Lambda-TechTalk)           |                   |
| Apr 5    | [Tech Talks](TechTalks.md)                       |  [Kafka](https://github.ncsu.edu/bramesh/KafkaDemo), [TerraForm](https://github.ncsu.edu/jbinkrot/terraform-tech-talk), [Puppet](https://github.ncsu.edu/dpatel12/DevOps-Puppet-Techtalk), [Packer](https://github.ncsu.edu/ppatel16/PackerTechTalk)          |                   |
| Apr 10   | [Tech Talks](TechTalks.md)                       | [Salt](https://github.ncsu.edu/kjadhav/salt-techtalk), [Docker Compose](https://github.ncsu.edu/itrust-no-one/tech-talk), [Spinnaker](https://github.ncsu.edu/scbutle2/tech-talk)           |                   |
| Apr 12   |                 |            |                   |
| Apr 17   | [Chaos Engineering](https://docs.google.com/presentation/d/1ZVRquK72cxqqSIY0OWU9wnA33UKDEPWz5UIcM2YBtJQ/edit#slide=id.p)                                 |            |                   |
| Apr 19   | Workshop                         |            |                   |
| Apr 24   | Demos                            |            |                   |
| Apr 26   | Demos                            |            |                   |
| May 8    | Final Exam (8:00am)              |            |                   |

### Resources

[Slack](https://csc519-spring2018.slack.com/)
[NC State - Stack Overflow](https://stackoverflow.com/c/ncsu/)

##### Papers

* [An empirical study on principles and practices of continuous delivery and deployment](https://peerj.com/preprints/1889.pdf)

##### Books

* [Effective DevOps](https://www.amazon.com/Effective-DevOps-Building-Collaboration-Affinity/dp/1491926309)
* [Ansible: Up and Running](http://www.ansiblebook.com/)
* [Continous Delivery](http://continuousdelivery.com/)
* [Continous Integration](http://www.amazon.com/Continuous-Integration-Improving-Software-Reducing/dp/0321336380)
* [Designing Data-Intensive Applications](http://dataintensive.net/)
* [Systems Performance: Enterprise and the Cloud](http://www.brendangregg.com/sysperfbook.html)
* [The Practice of Cloud System Administration](http://the-cloud-book.com/)
* [DevOps: A Software Architect's Perspective, SEI](http://www.amazon.com/DevOps-Software-Architects-Perspective-Engineering/dp/0134049845)

##### Glossary of Tools

* [http://newrelic.com/devops/toolset](http://newrelic.com/devops/toolset)
