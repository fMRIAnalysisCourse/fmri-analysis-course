# fMRI data analysis course

Materials for *fMRI data analysis* course taught at [Nicolaus Copernicus University](https://www.umk.pl/en/) in Toruń
for cognitive science students (including first-year students). The course covers fundamental topics in fMRI 
data analysis (in Python). 

### The Hogwarts way 
I called the way of teaching the course *the Hogwarts way*. It refers to the fact 
that for most participants, the fMRI data analysis, python programming, version control, etc. was like magic at the beginning of the course.
The goal of the course was to introduce topics of fMRI data analysis, reproducibility, 
Python, and version control, giving students a lot of **FUN**  and freedom. 
 

The most important goal of the course was to reduce the initial fear of trying something 
entirely new, which is, in fact, quite complex. 


:warning: **Content warning**:
The course includes a lot of *Harry Potter* content not suitable for muggles 
and too serious people.

### How to become *neuroinfomagician*?

![](images/fMRIDA_study_plan.png)


## General information

The course was supported by [DataCamp Classroom](datacamp.com/groups/education) and 
[GitHub Education](https://education.github.com/). 


#### Time
- **Lectures and practice**: 30h (split into 3h sessions, every two weeks)
- **Homework** (Jupyter Notebooks share via GitHub Classroom, DataCamp Python courses, poster preparation): ~50h (self work)
- **Total time required to finish the course**: ~80h

#### Grading 
Activity + Homework + Poster + Magic



## Content

### I. [Introduction to neuroimaging](https://github.com/fMRIAnalysisCourse/fmri-analysis-course/blob/master/00-introduction/00-fMRIDA_slides.pdf) & [open science](https://github.com/fMRIAnalysisCourse/fmri-analysis-course/blob/master/01-reproducible_neuroimaging/01-fMRIDA_slides.pdf) (3h)

##### Tools:
[Jupyter lab](https://jupyterlab.readthedocs.io/en/stable/), 
[Markdown](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet), 
[GitHub](https://github.com/)

##### Homework:
- GitHub Classroom: [fMRI Q&A in Markdown](https://github.com/fMRIAnalysisCourse/01-homework/blob/master/01-fMRIDA_homework.ipynb)
- DataCamp Classroom: [Introduction to Python](https://learn.datacamp.com/courses/intro-to-python-for-data-science)
- DataCamp Classroom: [Intermediate Python](https://learn.datacamp.com/courses/intermediate-python)

### II. [fMRI data manipulation in Python](https://github.com/fMRIAnalysisCourse/fmri-analysis-course/blob/master/02-fmri_data_manipulation_in_python/fMRIDA_27-03-2020.pdf) (3h)

##### Tools: 
[Matplotlib](https://matplotlib.org/), 
[Numpy](https://numpy.org/), 
[Nibabel](https://nipy.org/nibabel/), 
[Nilearn](https://nilearn.github.io/), 
[Pandas](https://pandas.pydata.org/)

##### Practice:
- [Structural MRI manipulation](https://github.com/fMRIAnalysisCourse/fmri-analysis-course/blob/master/02-fmri_data_manipulation_in_python/00-structural_mri_manipulation_solution.ipynb)
- [Functional MRI manipulation](https://github.com/fMRIAnalysisCourse/fmri-analysis-course/blob/master/02-fmri_data_manipulation_in_python/01-functional_mri_manipulation_solution.ipynb)
- [Dataframes manipulation in Pandas](https://github.com/fMRIAnalysisCourse/fmri-analysis-course/blob/master/02-fmri_data_manipulation_in_python/02-data_frames_manipulation_solution.ipynb)

##### Homework:
- GitHub Classroom: [fMRI data manipulation in Python](https://github.com/fMRIAnalysisCourse/02-homework)
- DataCamp Classroom: [Introduction to Data Visualization with Matplotlib](https://learn.datacamp.com/courses/introduction-to-data-visualization-with-matplotlib)

### III. [fMRI data preprocessing](https://github.com/fMRIAnalysisCourse/fmri-analysis-course/blob/master/03-fmri_data_preprocessing/fMRIDA_10-04-2020_%233.pdf) (3h)
##### Tools: 
[Nipype](https://nipype.readthedocs.io/en/latest/), 
[Porcupine](https://giraffe.tools/porcupine/TimVanMourik/SomeGiraffeExample), 
[fMRIPrep](https://fmriprep.readthedocs.io/en/stable/)

##### Practice:
- [Linear transformations in Python](https://github.com/fMRIAnalysisCourse/fmri-analysis-course/blob/master/03-fmri_data_preprocessing/linear_transformations.ipynb)
- [Preprocessing with Nipype](https://github.com/fMRIAnalysisCourse/fmri-analysis-course/blob/master/03-fmri_data_preprocessing/fmri_preprocessing_nipype.ipynb)

##### Homework:
- YouTube: [3Blue1Brown: Essence of Linear Algebra](https://www.youtube.com/watch?v=fNk_zzaMoSs&list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab) 
- DataCamp Classroom: [Exploratory Data Analysis in Python](https://learn.datacamp.com/courses/exploratory-data-analysis-in-python)

### IV. General Linear Model [Part 1](https://github.com/fMRIAnalysisCourse/fmri-analysis-course/blob/master/04-general_linear_model/fMRIDA_24-04-2020_%234.pdf) & [Part 2](https://github.com/fMRIAnalysisCourse/fmri-analysis-course/blob/master/04-general_linear_model/fMRIDA_08-05-2020_%235.pdf) (3h + 3h)

##### Tools: 
[Nistats](https://nistats.github.io/), 
[Nilearn](https://nilearn.github.io/), 
[Sklearn](https://scikit-learn.org/stable/)

##### Practice: 
- [Simple linear regression](https://github.com/fMRIAnalysisCourse/fmri-analysis-course/blob/master/04-general_linear_model/simple_linear_regression.ipynb)
- [Multiple linear regression](https://github.com/fMRIAnalysisCourse/fmri-analysis-course/blob/master/04-general_linear_model/multiple_linear_regression.ipynb)
- [GLM on fMRI data](https://github.com/fMRIAnalysisCourse/fmri-analysis-course/blob/master/04-general_linear_model/glm_on_fMRI_data.ipynb)

##### Homework:
- GitHub Classroom: [Linear & multiple linear regression](https://github.com/fMRIAnalysisCourse/03-homework)
- GitHub Classroom: [GLM analysis & fMRI results plotting](https://github.com/fMRIAnalysisCourse/04-homework)
- DataCamp Classroom: [Introduction to Linear Modeling in Python](https://learn.datacamp.com/courses/introduction-to-linear-modeling-in-python)
- DataCamp Classroom: [Statistical Thinking in Python (Part 1)](https://learn.datacamp.com/courses/statistical-thinking-in-python-part-1)

### V. [Functional connectivity](https://github.com/fMRIAnalysisCourse/fmri-analysis-course/blob/master/05-functional_connectivity/fMRIDA_05-06-2020_%236.pdf) & [machine learning on fMRI data ](https://github.com/fMRIAnalysisCourse/fmri-analysis-course/blob/master/06-machine_learning/fMRIDA_05-06-2020_%237.pdf) (3h) 
##### Tools: 
[Nilearn](https://nilearn.github.io/), 
[Scipy](https://www.scipy.org/)

##### Practice:
- [Brain parcellations](https://github.com/fMRIAnalysisCourse/fmri-analysis-course/blob/master/05-functional_connectivity/brain_parcellations.ipynb)
- [Seed-seed connectivity](https://github.com/fMRIAnalysisCourse/fmri-analysis-course/blob/master/05-functional_connectivity/seed-seed_connectivity.ipynb)
- [Seed-voxel connectivity](https://github.com/fMRIAnalysisCourse/fmri-analysis-course/blob/master/05-functional_connectivity/seed-voxel_connectivity.ipynb)
- [ML on fMRI data](https://github.com/fMRIAnalysisCourse/fmri-analysis-course/blob/master/06-machine_learning/machine_learning_fMRI.ipynb) 

##### Homework: 
- GitHub Classroom: [Seed-based functional connectivity](https://github.com/fMRIAnalysisCourse/05-homework)
- Poster assignment 
