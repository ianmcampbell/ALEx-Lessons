# Arcus Modular Education Support System (MESS)

#### Designer, Sheila Braun, MA; Programmer, Ian Campbell, MD PhD. Based on ideas formed at the Summer 2019 Arcus Education Retreat attended by Joy Payton, MS (Supervisor, Arcus Education) and Sheila Braun (Data Instructional Specialist II, Arcus Education)

Many of CHOP’s principle investigators and their teams have become interested in R and statistical analysis in R. In support of [the Arcus project at CHOP](https://arcus.reskubestage.research.chop.edu), one of our goals at [Arcus Education](https://education.arcus.chop.edu) is to create learning environments for relevant topics in which 100% of attendees spend 100% of their time working towards their own goals at their own pace. We have piloted our approach with R and Statistics workshops. 

In our workshops, 

* Each learner sets their own goals.    
* Each learner receives an individualized curriculum based on their goals.   
* Success is measured by the extent to which each learner perceives themselves to have met their own goals.

Workshop attendees have highly variable goals, from R basics to machine learning algorithms for genetic data to report writing for monthly metrics. We experimented with R packages to answer the question, “How can an instructor who has _N_ attendees at a workshop create _N_ different curricula based on _N_ different sets of learning goals, while still treating the class not so much as a single entity, but as _N_ individuals?” 

To answer this question in a practical way, we are currently using R packages such as `shiny` and `learnr` to create a tool that streamlines the process of designing individual curricula.

The software for this tool is in the [Personalized Learning Plan](https://github.research.chop.edu/braunsb/Arcus-Education-Lessons-and-Learning-Plan-Generator/tree/master/Personalized-Learning-Plan) folder. Individual lessons are in [Lessons](https://github.research.chop.edu/braunsb/Arcus-Education-Lessons-and-Learning-Plan-Generator/tree/master/Lessons). 

### MESS Around: Come to a Workshop!

All CHOP and Penn employees are welcome to attend our workshops. Registration is required. [Click here to find out more and to register](https://redcap.chop.edu/surveys/?s=EYWKYA48KT). 

### Be MESSy: Become a Contributor!

[New Lessons](https://github.research.chop.edu/braunsb/Arcus-Education-Lessons-and-Learning-Plan-Generator/tree/master/New-Lessons) is a folder for you, should you wish to become a MESS contributor. Please add your educational material to this folder. If you are a genetics expert, teach us about genetics; if you want people to know how to use a package you just created, create a lesson about it and add it. If you want to teach about Python, put your Python lessons there.

NOTE: The link works for CHOP employees only at the moment. 

These are our requirements for a lesson:

* It must be provided in Markdown (.Rmd is our favorite, but you may supply a .md file instead).
* It must stand on its own. If you have Python code that runs upon rendering, or SQL, or videos, or links, they must work. 
* It must adhere to CHOP's standards and ethics. 

Our editors will check your lesson and add it to the list of options available to learners if we believe it is in line with our mission to educate learners at CHOP. 

## For our Instructors: How to Add a Lesson

If you have created a lesson that you would like to make available to instructors as they create curricula for individuals or for groups, please follow these steps:

1. Fork this repo.
2. In your local Lessons environment, create a folder under "Lessons" called the lesson name with hyphens instead of spaces and *no uppercase letters*. Our system is case sensitive for folder names.
3. Put your lesson in the folder. Your lessons should be in .md or .Rmd format. If your actual lesson is in another format (for instance, if it is a Python notebook), please place a .md or .Rmd file in the folder that contains a link to your otherwise-formatted lesson. 
4. Add your lesson's information to the bottom of the ModuleTable.csv file. Choose a unique unit number and lesson name, then place the folder name in the next column formatted like this: /my-folder-name/
5. Save the module table file as a csv (don't change it to an xlsx file)
5. Push your forked version of the repo to GitHub.
6. Open a Pull request. If you have rights in the main Lessons repo, go ahead and accept the pull request. If you don't have rights, we'll respond as quickly as we can.
7. Send an email to Ian Campbell at campbellim@email.chop.edu telling him that you added a lesson. 
8. Ian will notify you when you can see your new lesson in the list of lessons available for curriculum web sites. :)

NOTES

* I found out the hard way that adding any other detritus (files, etc.) to the root directory "Lessons" results in the learning plan generator breaking.     
* If your lesson has supporting data, just plunk it into the folder that contains the lesson and use the name of the file alone as pathname from within your lesson document. 
* If what your lesson links to calls supporting data, you may keep that data whereever you like, provided that it is a public link that any leaner-instructor may access even if they don't have CHOP credentials. 

Thank you for adding to the list of lessons we can offer!


### Note about this Repo's History

Related to the repo inside CHOP's enterprise GitHub. 
