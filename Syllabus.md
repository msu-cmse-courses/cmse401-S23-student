# CMSE 401: Methods in Parallel Programming


[Link to Syllabus Table of Contents](#TOC)

----
<a name="Course Description"></a>
# Course Description

This course teaches parallel programming concepts with a focus on applications  encountered in science and engineering.  These “real world” problems are often larger than what can easily be solved using your personal computer.   

By the end of this course, you will be able to:

1. **_Give_** examples of major science and engineering domains which use parallel programming and the common types of algorithms which need large scale computing (ex. the seven dwarfs of HPC).
1. **_Demonstrate_** the ability to access, navigate and use a variety of Advanced Computing Systems with remote Linux connections. (ssh, module systems, bash, text editing, file systems, software install and building, environment variables, schedulers, etc). 
1. **_Analyze_** software by conducting profile and benchmark studies with different parameters and options. _**Explain_** the bottlenecks and scaling of the code and present results to peers with predictions of times and scaling. 
1. **_Summarize_** the fundamentals of parallel programming concepts including; strong and weak scaling, Amstels law, communication overhead, locks and racing conditions.
1. **_Explain_** differences between major parallel hardware and software paradigms. **_Compare_** and **_contrast_** the different approaches and be able to **_choose_** appropriate tools for a given problem. 
1. **_Develop_** and **_Evaluate_** parallel codes using a variety of major parallel paradigms including; pleasantly parallel, shared memory parallelization (ex. OpenMP), accelerator (ex GPUs and FPGAs), shared network parallelization (ex. MPI, Hadoop, and Charm++) and  parallel libraries (ex. cupy, numba, mkl, fftw and blas). 

We will work toward the goals expressed above throughout this course using a range of activities – primarily by writing software both individually and in small groups, but also through discussion, presentations, and other types of exercises.  


## Topics Covered

The primary topics covered in this course include:

* Linux/Bash programming/environment
* Software Profiling and Benchmarking
* SLURM Scheduling system
* Pleasantly Parallel Methods
* Shared memory Parallelization with OpenMP
* Shared Network Parallelization with MPI
* Accelerator Parallelization 


## Course Format and Activities

This course will be delivered in-person. 


### Class participation

Active class participation (led both by the instructors and by students) is critical to the success of this course.  As such, you are expected to attend every class session, bring the required materials and actively participate in the in-class discussion. 


### Pre-class assignments

We will assign short assignments that are due prior to class. The purpose of these assignments is to introduce new material and give you some exposure so that we can focus on hands-on practice during class. These assignments will typically consist of short videos, reading assignments, and related questions or problems. Each pre-class assignment includes a survey that students must fill out by 11:59 p.m. the night before class.  


### In-class programming assignments

Class sessions will be held three times a week and broken up into presentations, discussions, and programming activities that will allow you to immediately implement (and get instant feedback on) what you have just learned.  To gain credit for in-class assignments, students must show how much they were able to complete before leaving class. 

### Quizzes

You will have periodic in-class quizzes (approximately 1 quiz every three weeks) that will assess your understanding of materials covered in class. These quizzes are not intended to be high stress and therefore add up only to a small portion of the final grade. Instead the quizzes are primarily used as a tool by the instructor to help gage progress and adjust course materials to help improve individual learning. Quizzes will be taken during class and be turned in via the course [Desire2Learn](http://d2l.msu.edu/) page.


### Homework

Students will have periodic programming assignments (approximately 1 assignment every three weeks) that will provide a more in-depth exploration of the materials covered in class. These assignments may include both individual work and group work and will be turned in by the given deadline via the course’s Desire2Learn page. 

### Projects

Each student will complete an individualized 2-part project with milestones due throughout the semester (approximately 1 milestone every three weeks) that will provide a personalized exploration of the materials covered in class. These projects are assumed to be individual but group work may be considered with approval by the instructor. Student projects will be maintained and turned in by providing instructor read access to a git repository. 

### Final Exam:

The final exam will cover the entire course and will have a similar format to the Quizzes. However, instead of a single motivating question the final will have four motivating questions (likely with five parts each). The final exam will be conducted TBD. 

## Assessment Information

There are a variety of course activities, with percentages of total grade listed.  More detailed descriptions of each activity can be found elsewhere in the syllabus.  


| Activity | Grade Percentage |
|----------|------------------|
| Pre-Class Assignments | 20 |
| In-Class Participation |  20 |
| Homework Assignments | 20 |
| Project Milestones | 20 |
| Bi-weekly Quizzes | 10 |
| Final Exam | 10 |
| Total | 100% |


### Grading scale

4.0 < 90%, 3.5 < 85%, 3.0 < 80%, 2.5 < 75%, 2.0 < 70%, 1.5 < 65%, 0.0 < 60%. 


Note: grades will not be curved - your grade is based on your own effort and progress, not on competition with your classmates. 

---
# Logistical Information


## Course website

Information for this course is being managed via the course website:  

[https://msu-cmse-courses.github.io/cmse401-s23-student/](https://msu-cmse-courses.github.io/cmse401-s23-student/)

Accompanying course information, including the official course calendar, can be found at this website. Each section also uses a Desire2Learn page for assignment grading and organization, which can be found at [http://d2l.msu.edu](http://d2l.msu.edu). All assignments will be handed in via Desire2Learn. Consult the course website for instructions.

## Course Meeting Time and Location

* M W F 	10:20 - 11:40 Engineering Building 1230



## Course Schedule

Specific assignments and due dates will be maintained on the [course schedule](https://msu-cmse-courses.github.io/cmse401-S23-student/assignments/Schedule), which is linked to off the course website.  

## Required materials for class

The “in-class” programming assignments are a critical part of the learning process in this course. To that end, you will need to ensure that you have the following:

*   A computer to bring to class. 

The details regarding the software needed for this course are provided in the “Software Setup Guide” which will be provided to you by your instructor.


### Reading Materials

All required readings will be provided as Open Educational Resource (OER) via link on the course website. 

## Instructor Contact Information

-     Daniel Appelö (he/him)
    - Computational Mathematics, Science and Engineering & Department of Mathematics
    - Email: [appeloda@msu.edu](mailto:appeloda@msu.edu)

## Instructor office hours and locations

The best way to contact instructors is through email or by visiting their office hours. Please give your instructor 1 workday to reply to all emails. Office hours will be held just after class on for one hour.

| When | Where |
|------|-------|
| MW 9.00-10.00 | EGR 1225 | (Amit & Daniel)
| Thursday | EGR 1508b | (Amit)



# Course Policies and Expectations


## Class attendance 

This class is heavily based on material presented and worked on during class, and it is critical that you attend and participate fully every week! Therefore, class attendance is absolutely required. Since unexpected situations may arise, all students will be permitted to miss three class periods without penalty. After the first three, **_an unexcused absence will result in zero points for the day, which includes the in-class programming assignment points_**. Arriving late or leaving early without prior arrangement with the instructor of your session may be counted as an unexcused absence.  Note that if you have a legitimate reason to miss class (such as job, graduate school, or medical school interviews) you must arrange this ahead of time to be excused from class. Six or more unexcused absences will result in the reduction of your grade by one step (e.g., from 4.0 to 3.5), with additional absences reducing your grade further at the discretion of the course instructor. **_If you are unable to attend class or complete assignments due to illness or self-isolation (as per the CDC recommended guidelines), your instructor will work to provide the necessary accommodations to ensure that your performance in class is not significantly impacted._**

## Email

At times, we will send out important course information via email. This email is sent to your MSU email address (the one that ends in “@msu.edu”).  You are responsible for all information sent to your university email and for checking this account daily. 

## Inclusive classroom behavior 

Respectful and responsible behavior is expected at all times, which includes not interrupting other students, refraining from non-course-related use of electronic devices or additional software during class sessions, and not using offensive or demeaning language in our discussions. Flagrant or repeated violations of this expectation may result in ejection from the classroom, grade-related penalties, and/or involvement of the university Ombudsperson. In particular, behaviors that could be considered discriminatory or harassing, or unwanted sexual attention, will not be tolerated and will be immediately reported to the appropriate MSU office (which may include the MSU Police Department).

In addition, MSU welcomes a full spectrum of experiences, viewpoints, and intellectual approaches because they enrich the conversation, even as they challenge us to think differently and grow. However, we believe that expressions and actions that demean individuals or groups comprise the environment for intellectual growth and undermine the social fabric on which the community is based. These demeaning behaviors are not welcome in this classroom.

## Accommodations for Students with Disabilities

> Michigan State University is committed to providing equal opportunity for participation in all programs, services and activities. Requests for accommodations by persons with disabilities may be made by contacting the Resource Center for Persons with Disabilities at 517-884-RCPD or on the web at [http://rcpd.msu.edu](http://rcpd.msu.edu).  Once your eligibility for an accommodation has been determined, you will be issued a Verified Individual Services Accommodation ("VISA") form. Please present this form to the instructor at the start of the term and/or two weeks prior to the accommodation date (test, project, etc.). Requests received after this date may not be honored. 
>
>- from the Resource Center for Persons with Disabilities (RCPD)

## Academic honesty

Intellectual integrity is the foundation of the scientific enterprise.  In all instances, you must do your own work and give proper credit to all sources that you use in your papers and oral presentations – any instance of submitting another person’s work, ideas, or wording as your own counts as plagiarism.  This includes failing to cite any direct quotations in your essays, research paper, class debate, or written presentation.  The MSU College of Engineering adheres to the policies of academic honesty as specified in the General Student Regulations 1.0, Protection of Scholarship and Grades, and in the all-University statement on Integrity of Scholarship and Grades, which are included in Spartan Life: Student Handbook and Resource Guide.  Students who plagiarize will receive a 0.0 in the course.  In addition, University policy requires that any cheating offense, regardless of the magnitude of the infraction or punishment decided upon by the professor, be reported immediately to the dean of the student's college.  (See also the[ Academic Integrity](https://www.msu.edu/%7Eombud/academic-integrity/index.html) webpage.)

It is important to note that plagiarism in the context of this course includes, but is not limited to, directly copying another student’s solutions to assignments; copying materials from online sources, textbooks, or other reference materials without citing those references in your source code or documentation, or having somebody else do your in-class work or homework on your behalf.  Any work that is done in collaboration with other students should state this explicitly, and have their names as well as yours listed clearly.

More broadly, we ask that students adhere to the Spartan Code of Honor academic pledge, as written by the Associated Students of Michigan State University (ASMSU):

**_“As a Spartan, I will strive to uphold values of the highest ethical standard. I will practice honesty in my work, foster honesty in my peers, and take pride in knowing that honor is worth more than grades. I will carry these values beyond my time as a student at Michigan State University, continuing the endeavor to build personal integrity in all that I do.”_**

## Limits to confidentiality

Essays, journals, and other materials submitted for this class are generally considered confidential pursuant to the University's student record policies.  However, students should be aware that University employees, including instructors, may not be able to maintain confidentiality when it conflicts with their responsibility to report certain issues to protect the health and safety of MSU community members and others.  As the instructor, I must report the following information to other University offices (including the Department of Police and Public Safety) if you share it with me: suspected child abuse/neglect, even if this maltreatment happened when you were a child, allegations of sexual assault or sexual harassment when they involve MSU students, faculty, or staff, and credible threats of harm to oneself or to others. These reports may trigger contact from a campus official who will want to talk with you about the incident that you have shared.  In almost all cases, it will be your decision whether you wish to speak with that individual.  If you would like to talk about these events in a more confidential setting you are encouraged to make an appointment with the MSU Counseling Center.

## Changes to Syllabus

The syllabus may also be adjusted if needed. These types of changes will be announced during class, by email and/or in the course’s website.

## Commercialized Lecture Notes

All lectures, videos and notes provided in this course are copyrighted by the university.  Recording of lectures and/or commercialization of other university-provided course materials is not permitted in this course.

## Disruptive Behavior

Article 2.III.B.4 of the[ Student Rights and Responsibilities (SRR)](http://splife.studentlife.msu.edu/academic-freedom-for-students-at-michigan-state-university) for students at Michigan State University states: 

> "The student's behavior in the classroom shall be conducive to the teaching and learning process for all concerned." Article 2.III.B.10 of the[ SRR](http://splife.studentlife.msu.edu/academic-freedom-for-students-at-michigan-state-university) states that "The student and the faculty share the responsibility for maintaining professional relationships based on mutual trust and civility."

[ General Student Regulation 5.02](http://splife.studentlife.msu.edu/regulations/general-student-regulations) states: 

>"No student shall . . . interfere with the functions and services of the University (for example, but not limited to, classes . . .) such that the function or service is obstructed or disrupted. Students whose conduct adversely affects the learning environment in this classroom may be subject to disciplinary action through the Student Judicial Affairs office."

## Grief Absence Policy

Michigan State University is committed to ensuring that the bereavement process of a student who loses a family member during a semester does not put the student at an academic disadvantage in their classes. If you require a grief absence, you should complete the “Grief Absence Request” web form no later than one week after knowledge of the circumstance. I will work with you to make appropriate accommodations so that you are not penalized due to a verified grief absence.


# Using this Course’s Python Setup

**Instructions for downloading Anaconda (Python 3.x):**


1. Go to the Anaconda Download webpage: [https://www.anaconda.com/downloads](https://www.anaconda.com/downloads)
2. Pick your operating system.
3. Download the Python 3.x version (64 bit recommended).
4. Follow the directions at the bottom of the page to install Python on your specific operating system.
5. Open the command line program on your computer
    *   On windows, type CMD in the run box in the Start menu.
    *   On Mac, type “terminal” and hit enter in the Finder window
    *   On Linux, open up the console application
6. Type “jupyter notebook” in the command line and hit enter

If everything goes correctly, a browser window should open up with the Jupyter interface running. If things don’t work, don’t worry; we will help you get started.

**Instructions for connecting to the engineering JupyterHub server:**

Every student enrolled in this class will be given an engineering computing account. If this is your first time using your Engineering account you will need to activate the account by going to the following website:

[https://www.egr.msu.edu/decs/myaccount/?page=activate](https://www.egr.msu.edu/decs/myaccount/?page=activate) 

Enter your MSU NetID. The initial password will be your Apid with an @ on the end (example: A12345678@) and then they have to set a password that meets the requirements listed on the page. Verify the password. Then agree to the terms and Activate.

Once your account is activated you can access the classroom Jupyterhub server using the following instructions:


1. Open up a web browser and go to the following URL: [https://jupyterhub.egr.msu.edu](https://jupyterhub.egr.msu.edu) 
2. Type your engineering login name. This will be your MSU NetID.
3. Your engineering password.

If everything is working properly you will see the main “Files” windows in the Jupyter interface.

**Instructions for getting iPython notebook files into Jupyter:**

iPython notebooks (also referred to as Jupyter notebooks) are files that end with the .ipynb extension.  We will give you these files for all of your assignments, you will edit them and turn in the edited files using the class Website.

You can download the ipynb assignment files from the class website ([http://d2l.msu.edu](http://d2l.msu.edu)). Once you have an ipynb file you can load it into Jupyter using the “upload” button on the main “Files” tab in the Jupyter web interface. Hitting this button will cause a file browser window to open. Just navigate to your ipynb file, select it and hit the open button.

Once you see your filename in the jupyter window you can just click on that name to start using that file. 

**Instructions for making a copy of iPython notebooks and turning them in:**

When you are finished editing your iPython notebook and are ready to turn in the assignment you will need to download the ipynb file from the Jupyter interface.  



1. With the notebook file open in Jupyter, go to the “File” menu, select the “Download as” menu option and then choose “iPython Notebook (.ipynb)”
2. Pick a place to save the file (The desktop is a good choice).  
3. Make sure you make  a copy of the .ipynb file for your own records.
4. Go to the [Desire 2 Learn](http://d2l.msu.edu) course website and upload the .ipynb file into the assignment folder. 

**NOTE:**  Video versions of these instructions are available on the [CMSE YouTube Channel](https://www.youtube.com/channel/UCzs8QmQJ74xHmxRrq3QtvtQ). 

----
<a name="TOC"></a>

## Syllabus Table of Contents


[TOC]

----
