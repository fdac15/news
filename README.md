# Syllabus for "Fundamentals of Digital Archeology"
## [Dec 8 2:45-5:45] Final project presentations
  * In case earlier slots fill up

## [Nov 30] Final project presentations
* Full (four presentations already)

## [Nov 25] Final project presentations
* Please schedule by opening an issue on fdac15/news

## [Nov 23] Final project presentations 
* Please schedule by opening an issue on fdac15/news
  1. Skyrim

## [Nov 18-20] 
* Last questions related to final project

## [Nov 16]
* Last questions related to final project
* Instructions on how to use AWS

## [Nov 13] 
* Review session on various magic things we used
  1. (Re-)Introduction to R and modelling
  1. Please bring your final project questions!
  
## [Nov 11] 
* Review session on various magic things we used: [slides](https://github.com/fdac15/presentations/blob/master/db.pdf)
  1. Database history
  1. Mongodb
  1. Data structures, e.g., dictionaries
* If you had a large file thats stuck iin your git history where github refuses to accept yourt push, [BFG](https://rtyley.github.io/bfg-repo-cleaner/) claims to remove it easily

## [Nov 9-13] 
* Review session on various magic things we used: [slides](https://github.com/fdac15/presentations/blob/master/magic.pdf)
  1. Ports/Sockets/tunnels/firewalls
  1. Docker containers


## [Nov 4-6] 
* Session for questions on homework and final project
* Please don't forget to open a PR for your homework to "discovery" project

## [Nov 2] 
* Please open a PR for your homework to "discovery" project
  1. If it is in TXP1 or elswhere, just add yourGHhandle.md to discovery that indicats where it can be found
* Open topics: questions on final project
* Modelling: the question of transforming the data, anova vs regression, etc
* Data structures: How to convert from MongoDB to table?


## [Oct 28-30]
* Discuseed the homework assignment

## [Oct 26]
* If docker containers are running slow, I have created another set of containers on da3.eecs.utk.edu
   1. The home directory will still be the same
* If the mongodb on da0 is running slow, there is another instance of mongodb set on da1
   1. The databases on da0 and da1 are not shared, so you'll need to recreate them
   2. da1 is a sharded instance, so if you partition your database or collection, can run hadoop like processing on the three shards
* Notes on mongodb schemas on da0
   1. github collection repos has two types of records
      1. Retrieved via user/XXXX/repos where the resulting repos for each user are store in the field 'values'
      2. Retrieved via repositories API, where is not much useful info (and no field 'values')
   1. github and bitbucket repos have different fields

## [Oct 23]
* Storage assignment is due
*  We will discuss issues with the assignment and how to proceed to the next step.
  * For measures you can do any of the following
     1. use bitbucket or github: both have a number of fields that are similar
     1. use additional collections in Top40Forges database that contain several fields
        1. e.g. Launchpad
     3. get additional attributes for the forges that you have selected by scraping project pages
  * Even if you do not have all the desired predictors/response, please pose a hypothesis on 
     1. How the response should covary with predictors
     2. How that relationship might vary betwen the two forges
* Discuss any issues arising in final projects

## [Oct 19, 21]
* Class time dedicated to coordinate work on final project

## [Oct 16]  Fall break

## [Oct 14]
* Data storage/ and initial analysis assignment
* Please complete the [spreadsheet](https://docs.google.com/spreadsheets/d/1Wbc4ZONGnNoY15x8jaComQu_2SUrMdlsJgDTHfAyfpM/edit?usp=sharing): Forges 11, 21, 22, 24, 29, 33, 40 are missing. Many of them are inaccessible or in other ways less interesting, but please post your results into the notes field if no data could be obtained. 

## [Oct 12]
* Formal proposals with the objective workplan, etc. for the final project will be presented.

## [Oct 9]
* Formal proposals with the objective workplan, etc. for the final project are delayed until Oct 12
* No need to change goals and motivation if they stay the same as in the sales pitch.
* Key new pieces I am looking for in the project proposal:
  * Work breakdown, assignment, and schedule
     1. What, When, Who?
     1. One or two intermediate deliveries with the final delivery before Dec 3?
     1. What data will be needed, how it will be retrieved and processed?
     1. What needs to be done first? E.g., dependencies among tasks.
     1. Element of risk management: if something does not work, what alternatives will be tried?

1. Why project plans are needed?
   1. to practice project management
   1. to reduce the risk to the final project


## [Oct 7]
* Class time reserved for groups to meet and prepare the workplan, primary assignments, and schedule for the final project.

## [Oct 5]
* Final project selection: A representative from each project please send me:
  1. The name of the project repository
  1. The list of members
* Final report on Discovery project T5-8 + last repository of T4
  1. I still don't see all the projects in the google spreadsheet (link from Discovery project)
 
## [Oct 2]
* Final report on Discovery project
* Final project selection: everyone will have a project to work on

## [Sep 30] 
* Will finish modelling lecture
* Remaining Final Project sales pitches

## [Sep 28] Final Project sales pitch, Discovery status
* A few proposals for the final project will be presented
* The progress update on the discovery project
  1. The data collection is, presumably over
  2. This week analyze the results and present the results on Friday (short 3-4 min presentations)
  3. The spreadsheet linked from fdac15/discovery is still empty
* Other matters

## [Sep 25] R/Modelling + AWS + Final Project instructions
* Updated AWS instructions for discovery (see fdac15/discovery, fdac15/aws)
* Created FinalProject repo with some instructions (see fdac15/FinalProject)
* Will finish R presentation, the modelling part

### [Sep 23] Introduction to R/modeling
  * Will go over the presentation in fdac15/stats
  * AWS instructions for discovery (see fdac15/discovery)

### [Sep 21] Introduction to R/modeling
   * Progress report on the project: Each team provides a 3 min verbal summary of what they achieved so far and what they plan to do. Challenges:
      1. Google search API exhausted (utilize other ip on amazon, see below)
      2. Google search asks for captchas (use bing)
      3. No public repositories on some forges
      4. Different (non-REST) apis
      5. Forge has been decomissioned
   * Presented example of binomial distribution/R (fdac15/stats)
   
### [Sep 18] The remaining three presentations: Groups 3, 2, 1
   * Answers to any questions related to the project
   * Comments for presentations given on Sep 16
      1. What is binomial distribution and how to use it?
      1. More elaborate term selection: Bigrams/Trigrams
   * Potential [data sources](https://github.com/fdac15/news/blob/master/datasources.md) for the final project
   
### [Sep 16] Great presenters today!
   * We heard representatives from group 6, 5, and 4. 

### [Sep 14] Discovery
   * Finish data discovery lecture and discussed a new assignment
   * Selected Presentations for the entire class
      1. Please vote if you have not done so
      1. Since the results are not yet available, the selected presentations will be delayed until Wednesday
      1. I am very impressed with the presentations I have seen on Friday and with the ones I have had a chance to read so far, great work!
   * Think about final project
      1. Involves data discovery/retrieval/storage/analysis/presentation
      1. Try to find topic that you like or data that you want to analyze
      1. Prepare a presentation to recruit others to join your project
      1. It will have a four page final report
      1. Examples of final projects done last year at http://github.com/fdac/ 
   
### [Sep 11] Prallel presentations in class
   * Six groups presenting in parallel: presentation is 5min+2m questions
   * Agree on a person to send to next round: each participant in a group gets one vote cast for the presentation (not theirs) they favor: the vote is cast as a comment for an issue naming their group.
   * Groups were obtained using a complicated text analysis to get representation of different groups, similarities and dissimilarities of text in commits and issues 
      1. jtyler7 joseph346  chumekaboom kylebshr nwilder0 gsimpson723 
      1. rerwin21 ryanwagn kdunn13 teaguejt awachte tjonesster 
      1. matsuobasho stonecoldhughes justa-ghost w4d3 sbradfo5 tapjdey
      1. ryancaldwell1 jlong49 codyjae jaredmichaelsmith davpcunn spicychckn
      1. beamad12 almasaeed2010 mbenkhayal milanjpatel rroper1 inthesunset cwilker
      1. millermoore nateige jalomas7 rhoque-icl mtwe curtis017 alexklibisz

   * Here is what the presentation should touch upon
      1. What is the question?
      1. What was the approach?
      1. What problems did I encounter?
      1. What results did I get?
      1. What new ideas did this generate?
   * The list of problems encountered will be collected and summarized 

   
### [Sep 9] All have committed and raised/received issues: Congratulations!
   * The current stats on commits/issues are at https://github.com/fdac15/Assignment1/Astats.ipnb
   * The lecture material is at https://github.com/fdac15/presentations dd.pdf
   * Example of using the stemmer at the end of https://github.com/fdac15/Assignment1/Astats.ipnb
   * How to enable R in ipython notebook: will restart docker containers Sunday at 5AM, if it is an issue for you (are running a long script) please let me know. The home directory/files will be preserved.
   * Look forward to presentations on Friday!

### [Sep 7] Labor day!
   * Great progress on Assignment1! A few notes:
      1. Please crete an issue commonting on your peer's project (above you in the dendrogram) if you have not done so yet.
      2. Please write at least a paragraph interpreting the observed differences, e.g.,
         a. Do differences between authors appear to be larger or smaller (or the same) as differences within book of the same author? 
         b. Why?

### [Sep 2, Sep 4] Work on the Assignment1 with your peers

### [Aug 31] Work on the Assignment1 with your peers
  * Guttenberg is already blocked
     1. Download to your laptop then scp to da2:Assignment1 
     2. Follow example at the end of the latest version of Assignment1.ipnb to red data from file
  * Text is public domain (sowhere on the web) but not on PG
     1. Use appropriate url to the text
  * Text is spread over multiple URLs
     1. Follow example at the end of the latest version of Assignment1.ipnb

### [Aug 28] Questions related to the assignment
  * How to copy files from/to docker container?
     1. In Mac/Linux (da2 is the host entry in ~/.ssh/config as described below) 
      ``` 
      scp -P YOURPORT fileToBeCopiedTo da2:Assignment1
      scp -P YOURPORT da2:Assignment1/fileToBeCopiedFrom .
      ```
      
     2. Using windows: putty has pscp command line that is similar to scp, but winscp provides more "windows-like" experience. Change the netid from audris to your netid and also change the port from 9001 to your port (to be found in students/ports.md).
     ![winscp](https://github.com/fdac15/news/blob/master/winscp.png "winscp")

### [Aug 26] Assignment1 has been introduced
  * Please fork and clone: let me know if you have any issues
  * Please make sure you go to settings -> enable issues after the fork
  * To your peer's fork is at https://github.com/PEERsGITHUBID/Assignment1
  * Will be discussing questions issues during class of [Aug 28]
  * Pay attention to the schedule of activities (Social workflow) in fdac15/Assignment1

### [Aug 24] Homework Due Aug 26
  * Some of you already submitted it :-) [fdac15/Homework0](https://github.com/fdac15/Homework0): this is an exercise of:
    1. using git command line in your docker container
    2. playing with ipython notebook
  * If you were not in the class Aug 21, please take a look at the presentation tools.pdf
       in https://github.com/fdac15/presentations
  * The lecture slides for today are in prelim.pdf at https://github.com/fdac15/presentations
  * Please let me know if the ssh/notebook are still not working for you

### [Aug 21] Homework Due Aug 24
  * Please make sure your ghid.md file is not empty and contains meaningful info: check if your .md file is there and not empty and, if not, please submit a pull request.
  * I am still waiting for pull requests with .md file and ssh (in lists.txt) from several of you, please submit your ghid.md file and public ssh key if you have not done so yet. I need it to add you to the class organization on github and key to enable paswordless login
  * Please accept github group membership: I am adding you to the group once you submit a pull request, but you still need to accept it. Some of the homeworks and slides will be in private repositories for which you will need group membership. 
  * Please try to ssh to da2 using windows (or mac/linux) instructions: if you are able to do that, then on your laptop browser please enter http://localhost:8888 to access your personal ipython notebook server. You can create python2, python3, and R notebooks. We will primarily use python3 and, later in the course, R
  * If you'd prefer to run the ipython notebooks on your own laptop (not from the sever) please install docker infrastructure per https://www.docker.com/toolbox. 
      * The docker image used for the class is audris/ipython-pymongo:v15
      * You will need to forward the port 888 to port 8888 on that docker container on your laptop
      * You will also need to start 'ipython notebook --no-browser' in the container
  * The slides for the lecture today (tools.pdf) are in https://github.com/fdac15/presentations

### [Aug 19] As noted in the initial assignement please create github id and ssh key, then fork and create a PR

### [Configuring ssh]
  * On linux/mac either 
    * create .ssh/config
    	1. create ~/.ssh/config
        ```
         host da2
            hosthostname da2.eecs.utk.edu
            port YOURPORT from students/ports.md
            username YOURNETID
         ```

        1. place your private key in ~/.ssh/id_rsa
        1. Make sure permissions are right
         ```
          chmod -R og-rwx ~/.ssh
         ```
        1. ssh da2
    * Or ssh directly 
      ```
       ssh -pYOURPORT -L8888:localhost:8888 -i id_rsa yournetid@da2.eecs.utk.edu
      ```

  * Putty is a common ssh client for windows
  * [Instructions on how to generate ssh key running windows](https://docs.joyent.com/public-cloud/getting-started/ssh-keys/generating-an-ssh-key-manually/manually-generating-your-ssh-key-in-windows)
    1. ![public ssh key from puttygen](https://github.com/fdac15/news/blob/master/puttykey.png "public ssh key from puttygen")
    1. Save the private key and use it in your putty ssh session
    1. Copy the public key (highlited in the image) to add to the list.txt 
    1. Now work on creating and saving session: start putty and go to connection/ssh/tunnels, enter source and destination and click *add*
    1. ![port forwarding](https://github.com/fdac15/news/blob/master/puttyport.png "select port forwarding")
    1. Go to  go to connection/ssh/Auth and browse for your private key
    1. ![authentication](https://github.com/fdac15/news/blob/master/puttyauth.png "select secret key that was saved above")
    1. Go to  go to session enter hostname and *YOUR PORT* from ports.md in fdac15/students
    1. ![session](https://github.com/fdac15/news/blob/master/puttysession.png "start putty session")
    1. Don't forget to _save_ the session before clicking open  



# Syllabus for "Fundamentals of Digital Archeology"
* **Course:** [COSCS-445/COSCS-545][class-site]
* ** MK405  2:30-3:20 MWF**
* **Instructor:** Audris Mockus, [audris@utk.edu](mailto:audris@utk.edu)
* **TA:** Tapajit Dey, [tdey2@vols.utk.edu](mailto:tdey2@vols.utk.edu)
* **Need help?**

Simple rules for questions: 

1. There are no stupid questions. 
1. Think of what the right answer may be.
1. Search online: stack overflow, etc.
  * code snippets: [gist.github.com](https://gist.github.com/)
  * answers to questions: [Stack Overflow](http://stackoverflow.com/)
1. Look through [issues](https://github.com/fdac/syllabus/issues)
1. Post the question as an issue
1. Office hours: MON: 1 pm - 2:20 pm, TUE: 9:45 am - 11 am. Location: MK620
     -- TA himself is a student in the class, so he might not be able to assist with everything.
	However, feel free to contact him if you are having any problems or need any resources to help with anything. 	Even if he is not able to solve everything, he can bring the problem to the instructor's attention. 
1. Ask instructor: [email](mailto:audris@utk.edu) for 1-on-1 help, or
   to set up a time to meet 

## Objectives
The course will combine theoretical underpinning of big data with
intense practice. In particular, approaches to ethical concerns,
reproducibility of the results, absence of context, missing data,
and incorrect data will be both discussed and practiced by writing
programs to discover the data in the cloud, to retrieve it by
scraping the deep web, and by structuring, storing, and sampling it
in a way suitable for subsequent decision making.  At the end of the
course students will be able to discover, collect, and
clean digital traces, to use such traces to construct meaningful
measures, and to create tools that help with decision making.

## Expected Outcomes
Upon completion, students will be able to discover, gather, and analyze
digital traces, will learn how to avoid mistakes common in
the analysis of low-quality data, and will have produced a working
analytics application.

In particular, in addition to practicing critical thinking,
students will acquire the following skills:
*  Use Python and other tools to discover, retrieve, and process data.
  
*  Use data management techniques to store data locally and in the cloud.
  
*  Use data analysis methods to explore data and to make predictions.

## Course Description

A great volume of complex data is generated as a result of human
activities, including both work and play. To exploit that data for
decision making it is necessary to create software that discovers,
collects, and integrates the data.

Digital archeology relies on traces that are left over in the course
of ordinary activities, for example the logs generated by sensors in
mobile phones, the commits in version control systems, or the email
sent and the documents edited by a knowledge worker. Understanding
such traces is complicated in contrast to data collected using
traditional measurement approaches.

Traditional approaches rely on a highly controlled and well-designed
measurement system. In meteorology, for example, the temperature is
taken in specially designed and carefully selected locations to
avoid direct sunlight and to be at a fixed distance from the ground.
Such measurement can then be trusted to represent these controlled
conditions and the analysis of such data is, consequently, fairly
straightforward.

The measurements from geolocation or other sensors in mobile phones
are affected by numerous (yet not recorded) factors: was the phone
kept in the pocket, was it indoors or outside?  The devices are not
calibrated or may not work properly, so the corresponding
measurements would be inaccurate.  Locations (without mobile phones)
may not have any measurement, yet may be of the greatest interest.
This lack of context and inaccurate or missing data necessitates
fundamentally new approaches that rely on patterns of behavior to
correct the data, to fill in missing observations, and to elucidate
unrecorded context factors. These steps are needed to obtain
meaningful results from a subsequent analysis.

The course will cover basic principles and effective practices to
increase the integrity of the results obtained from voluminous but
highly unreliable sources.

*   Ethics: legal aspects, privacy, confidentiality, governance
   
*   Reproducibility: version control, ipython notebook
   
*   Fundamentals of big data analysis:
    extreme distributions, transformations, quantiles,
    sampling strategies, and
    logistic regression

*   The nature of digital traces:
    lack of context,
    missing values, and
    incorrect data

## Prerequisites

Students are expected to have basic programming skills, in
particular, be able to use regular expressions, programming concepts
such as variables, functions, loops, and data structures like lists
and dictionaries (for example, COSC 365)

Being familiar with version control systems (e.g., COSC 340), Python
(e.g., COSC 370), and introductory level probability (e.g., ECE 313)
and statistics, such as, random variables, distributions and
regression would be beneficial but is not expected. Everyone is
expected, however, to be willing and highly motivated to catch up in
the areas where they have gaps in the relevant skills.

All the assignments and projects for this class will use github and
Python. Knowledge of Python is not a prerequisite for this course,
provided you are comfortable learning on your own as needed. While
we have strived to make the programming component of this course
straightforward, we will not devote much time to teaching
programming, Python syntax, or any of the libraries and APIs.  You
should feel comfortable with:

1. How to look up Python syntax on Google and StackOverflow.
1. Basic programming concepts like functions, loops, arrays, dictionaries, strings, and if statements.
1. How to learn new libraries by reading documentation and reusing examples
1. Asking questions on StackOverflow or as a GitHub issue.


### Requirements

These apply to real life, as well.

* Must apply "good programming style" learned in class
    * Optimize for readability
* Bonus points for:
    * Creativity (as long as requirements are fulfilled)

## Teaming Tips

* Agree on an editor and environment that you're comfortable with
* The person who's less experienced/comfortable should have more keyboard time
* Switch who's "driving" regularly
* Make sure to save the code and send it to others on the team

## Evaluation

* Class Participation – 15%: students are expected to read all
   material covered in a week and come to class prepared to take
   part in the classroom discussions. Responding to other student
   questions (issues) counts as classroom participation.

* Assignments - 40%: Each assignment will involve writing (or modifying a template of)
   a small Python program.

* Project - 45%: one original project done alone or in a group of 2 or 3
   students. The project will explore one or more of the themes covered
   in the course that students find particularly compelling.  The
   group needs to submit a project proposal (2 pages IEEE format)
   approximately 1.5 months before the end of term.  The proposal
   should provide a brief motivation of the project, detailed
   discussion of the data that will be obtained or used in the project,
   along with a time-line of milestones, and expected outcome.

## Other considerations

As a programmer you will never write anything from scratch, but will
reuse code, frameworks, or ideas.  You are encouraged to
learn from the work of your peers. However, if you don't try to do
it yourself, you will not learn. [Deliberate practice][deliberate-practice]
(activities designed for the sole purpose of effectively improving
specific aspects of an individual's performance) is the only way to
reach perfection.

Please respect the terms of use and/or license of any code you find,
and if you re-implement or duplicate an algorithm or code from
elsewhere, credit the original source with an inline comment.

## Initial assignment (Due Aug 21)

1. GitHub
   * Sign up for [GitHub](https://github.com/) if not already signed
     up. Pick default (free plan).
   * [Create ssh key](https://help.github.com/articles/generating-ssh-keys/)
      - Do steps 1, 2, 4, and 5
      - Do Not Share Your Private Key in id_rsa
   * [Fork](https://help.github.com/articles/fork-a-repo/) and create a [pull request](https://help.github.com/articles/using-pull-requests/) on
      [students repository](https://github.com/fdac15/students) so I
      can add you to the to the GitHub group for the course.
	  1. Start by [**forking** the students repository](https://github.com/fdac15/students)
	  1. Add your GitHub username as USERNAME.md (click on '+' - add 
         new file next to the https//<span></span><span></span>github.com/fdac15/students/+ link)
          1. Add your netid and publickey key (in id_rsa.pub) to list.txt
	  1. Click on Create Pull Request
1. Familiarize yourself with GitHub workflow
   * Walk through [workflow](#workflow) 
    
## Workflow
1. To start, [**fork** the repository][forking] for the exercise/project (found under [github.com/fdac15](https://github.com/fdac15))
1. [**Clone**][ref-clone] the repository to your computer.
1. View, create, and edit your ipython notebooks or other files
1. [**commit**][ref-commit] changes to complete your solution.
1. [**Push**][ref-push]/sync the changes up to GitHub.
1. [Create a **pull request**][pull-request] on the original
   repository by the due time (generally within a week)
1. You can continue to push fixes and improvements until the close
date – just add a comment in the pull request to let me know it's been updated.

Feedback will be given in the pull request, so please respond with
your thoughts and questions!  You are welcome to open the pull
request as the work is still in-progress if you are stuck and want
to ask a question – just mention `@audris` with the question to make
sure I know to look at it sooner.

## Resources
### Materials

This class assumes you are confident with this material, but in case you need a brush-up...

* Codecademy – [Python](http://www.codecademy.com/courses/python)
  and [Python Dictionaries](http://www.codecademy.com/courses/python-beginner-en-pwmb1/2/1?curriculum_id=4f89dab3d788890003000096)
* See also – [Other](#other)

#### Other

* [Mining the Social Web, 2nd Edition](http://shop.oreilly.com/product/0636920030195.do)
* [Interesting data visualizations using D3.js and more](https://www.jasondavies.com/)

##### Databases

* <https://github.com/variety/variety> - A MongoDB Schema Analyzer. One JavaScript file that you run with the mongo shell command on a database collection and it attempts to come up with a generalized schema of the datastore. It was also written about on the official MongoDB blog.

##### R and data analysis
* Modern Applied Statistics with S (4th Edition) by William
  N. Venables, Brian D. Ripley. ISBN0387954570
* [R](https://www.coursera.org/course/compdata) 
* [Code School](http://www.codeschool.com/courses/try-r)
* [Quick-R](http://www.statmethods.net)

##### Tutorials written as ipython-notebooks
* [python-data-cleaning](http://nbviewer.ipython.org/github/ResearchComputing/Meetup-Fall-2013/blob/master/python/lecture_21_pandas_processing.ipynb)
* [python tutorial for engineers](http://nbviewer.ipython.org/gist/rpmuller/5920182)

#### GitHub

* Git and GitHub
    * [Official GitHub Help](https://help.github.com/)
	* [GitHub Issues](https://guides.github.com/features/issues/)
    * [Recommended resources](https://help.github.com/articles/what-are-other-good-resources-for-learning-git-and-github)
* GitHub Pages
    * [Official site](http://pages.github.com/)
    * [Thinkful guide](http://www.thinkful.com/learn/a-guide-to-using-github-pages/)


<!-- Links -->
[docker]:http://www.eecs.utk.edu/resources/it/kb/docker
[class-site]:http://web.eecs.utk.edu/~audris/fdac
[deliberate-practice]:http://www.psy.fsu.edu/faculty/ericsson/ericsson.exp.perf.html
[pull-request]:https://help.github.com/articles/creating-a-pull-request
[create-repo]: https://help.github.com/articles/create-a-repo
[forking]: https://guides.github.com/activities/forking/
[ref-clone]: http://gitref.org/creating/#clone
[ref-commit]: http://gitref.org/basic/#commit
[ref-push]: http://gitref.org/remotes/#push
[pull-request]: https://help.github.com/articles/creating-a-pull-request
[raw]: https://raw.githubusercontent.com/education/guide/master/docs/forks.md
