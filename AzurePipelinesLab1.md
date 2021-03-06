# Lab 1: Creating Azure DevOps project

## Task 1: Create the Azure DevOps Team Project

1. Open a browser and navigate to your Azure DevOps organisation. The old URL is  https://youraccountname.visualstudio.com and will work indefinitely or the new URL is https://dev.azure.com/yourorganisationname.

2. In your Azure DevOps organisation select Create Project.

<img src="images/Lab1_1.png" width="624"/>

3. Give the project a name, e.g. "PipelineHOL". Make sure that version control is set to Git (select Advanced to show the options) and click Create. You could equally choose to use TFVC but this lab has documented the steps for using Git.
   
<img src="images/Lab1_2.png" width="424"/>

4. Your Azure DevOps team project has been created. You can add other people to the team if you want.

<img src="images/Lab1_3.png" width="624"/>

## Task 2: Cloning the Azure DevOps git repository to your local machine

Now your project is created it has an empty git repository ready for our use. To facilitate the lab we will need to put some code into this Repo as we need something to build and deploy in our pipelines. Note: Azure Pipelines can get code from other source code repositories like GitHub, Bitbucket etc.. however in this lab we will use the Azure Repos service built into Azure DevOps.

1. Head to Azure Repos using the menus on the left hand side. By default it should select the first sub-menu for files which is the area we want.
   
<img src="images/Lab1_4.png" width="624"/>

2. Azure Repos will tell us that the Repo created is currently empty and provides instructions for multiple ways to push code into this repository. For the lab today we are going to import the code from another repository so we will simply select the option to "import".
 
<img src="images/Lab1_5.png" width="624"/>

3. We will import the code from my existing GitHub repository by using the following clone URL (https://github.com/colinbeales/AzurePipelinesHOL-Codebase.git) then select "import" and give a few seconds for the repository to be ready for use. You now have a complete copy of the repository and don't need my GitHub repo again. If you ever make any changes to the code you can do this in isolation within your own repository hosted in Azure Repos.

<img src="images/Lab1_6.png" width="424"/>
  
[<- Lab: Overview](https://github.com/colinbeales/AzurePipelinesHOL/blob/master/README.md) | [Lab 2: Create a continuous integration build ->](https://github.com/colinbeales/AzurePipelinesHOL/blob/master/AzurePipelinesLab2.md)