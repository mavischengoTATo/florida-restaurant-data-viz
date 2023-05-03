# ANLY 503 Project Repo

This is the team repository you will be use for your 503 project. All your team's work will happen here. 

Links of interest:
* The project requirements are in the [`instructions.md`](instructions.md) document
* The repository structure is described in the [reposity structure section](#repository-structure) below
* You **will** make changes to this `README.md` file within your repository. These changes are descripned in the [instructions section](#instructions-for-modifying-this-readmemd-file) below.

## Repository structure

You will work within an **organized** repository and apply coding and development best practices. The repository has the following structure:

```.
├── README.md
├── code/
├── data/
├── img/
└── website/
```

* The `code/` directory is where you will develop all your code.  You may add additional sub-directories as needed to modularize your development.

* The `data/` directory should contain your data files and should have multiple sub-directories (i.e. raw, processed, analytical, etc.) as needed.

* The `img/` directory should contain any external images that you need for your site. However, all your viz's should be generated programmatically in your source code.

* The `website/` directory where the website will be deployed. It must be self-contained and accessible via an index.html within this sub-directory.  Any website asset (images, html, css, JavaScript source code) must be added to this directory. 

There is an empty placeholder file in each subdirectory called `placeholder-to-be-deleted.txt`. This file may be deleted **after** you save other files in those subdirectories. This file is needed to be able to keep the empty directory in the repo.

Other files we expect to see at the top level of this repo may include:
- `.gitignore`


## Elements that impact the distributions of restaurants in Florida on different dimensions

### Team section: Group 33: Zijing Cheng (zc233) & Nianqing Chen (nc807) & Zixuan Li (zl483)

### Summary section: 
Here, we divide into four parts, introduction, overview, exploration and conclusion
For introduction part, we learn the description of yelp dataset and choose to use resturants to do the analysis. At the same time, we do the EDA to further understand chosen sub dataset.

Through the initial EDA(overview part), we decided to conduct an in-depth analysis of restaurants in Florida, roughly divided into two directions, one is distribution analysis, and the other is statistical analysis.
By drawing different types of interactive graphs to show the relationship between variables, it gives us an in-depth understanding of different levels of data, and helps us understand the food culture, customs, surrounding environment, and geographical location on restaurant stars and reviews. influence level. The effective information provided by this dataset is comprehensively explored and demonstrated.

For the exploration part, we have carried out detailed statistics and induction on the categories of restaurants, and have carried out certain screening, induction and summary, and obtained a brand new dictionary of restaurant categories. At the same time, we have made full use of the data Collect the geographic location data provided to us and combine it with the business status, rating score, and count of reviews of restaurants in Florida. It shows its status distribution in real life, which is more conducive to us to summarize the surrounding environment of the restaurant, and provides us with a new perspective and thinking.







### Description: 
we divided code part into data_cleaning, data_analysis and eda.
In data_cleaning, we have clean process in R and Python and you can find them here.
In eda, we have initial data exploration and introduction of this project, as a question exploration part.
In img, we use serveral images to show the loaction of Tampa Bay and Florida.
In website, we have the main analysis website html, and introduction html, we haven't make it into be a website, but the we finishi the main part and we will divide the main analysis website into serveral part to tell the story in the final version.

The README.md file in a repository usually contains additional information about your project. Currently this file contains information about the repository structure. However, for the wip and final submissions, you will make the following changes to this file:

* You can delete the current content of the `README.md` file
* Add a project title section
* Add your team section with your team number and team member names
* Add an executive summary section describing your project
* Provide a description of all your code files, datasets, etc.


