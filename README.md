# Employability-Assessment-Tool
this is a project based on the data analytics on data set "candidates.xlsx" which contains the details of all the candidates who appeared for the online exam


     Final Project 2 - Employability Assessment Tool\n",
  
    "The dataset **candidates.xlsx** contains the test result of students who gave an online test for job.\n",

    "**The confidentiality of this dataset has been maintained by changing names, email address and userid of all the students.**\n",
 
    "The test consisted of several questions divided in 5 different sections. This dataset has total score as well as section wise scores of each student.\n",

    "You can download the data from : \"link\"\n",
 
    Dataset description
  Alloted Set - It contains number of set from 1 to 5.
    "- Total Score - It contains the total marks scored by the student.\n",
    "\n",
    "There are 5 different sections and 3 feature columns (given below) for every sections.\n",
    "\n",
    "- Section **n** - Total questions attempted\n",
    "- Wrong Answers **n** - Incorrect attempts\n",
    "- Marks **n** - Correct attempts\n",
    "\n",
    "(n stands for section number)\n",
    "\n",
    "### Perform appropriate operations and analytics on the dataset and find the answer of the following questions.\n",
    "\n",
    "1. Remove the NaN coloumns. Remove the Rows that contain NaN. Drop all the irrelevnt coloumns.\n",
    "2. Rename the coloumn names to proper ones.\n",
    "3. Capitalize the first letter of the names of students.\n",
    "4. Print the total number of unique sets. Drop any set if it contains extremely less data.\n",
    "5. Print the count and percentage of students in each set.\n",
    "6. Print the set-wise total number and the set-wise percentage of students who have scored more than 40 in total marks.\n",
    "7. Plot a bar graph of Number of Students vs Alotted Set.\n",
    "8. Plot a Histogram for Total Score. There should be 5 histograms for every set.\n",
    "9. Plot a scatter plot for section wise marks vs total marks for each section. Use subplot. Also use different colours for different range of total marks (0-40,40-60,60-100)\n",
    "10. **BONUS QUESTION: Out of the 5 sections, 2 sections have a high correlation. Find those sections and prove by a valid plot/graph/chart/table with a proper reasoing statement. (1 point)**\n",
    "\n",
    "11. Print the maximum and minimum marks scored in each section. Which section has got highest maximum marks? Which section has got lowest maximum marks.\n",
    "12. Print the name of toppers for each section. If there are multiple topper students in any section, print the count and names of all of them.\n",
    "13. Plot a stack bar plot of sectionwise scores of the topper.\n",
    "14. Print the names of students in every section who have secured the maximum Correct/Total ratio. If there are multiple topper students in any section, print the count and names of all of them.\n",
    "15. Find out if there is any student who is topper in both above questions (section wise). Such students will be called scholars. Prints the names of all scholars.\n",
    "16. Print the names of students who scored zero.\n",
    "17. Find the count of all students whose Incorrect/Correct Ratio in all sections is more than 1.\n",
    "18. **BONUS QUESTION: For the scholars mentioned above, extract their test result from the original data and convert it in a table of marks format. Write it to a text file. Then write a code to send the mail to all those candidates congratulating them for good performance. (2 points)**"
   
      
       
       "   Sr No.         Username                   Name                    Email  \\\n",
       "0       1      usmjtsrkrsl       jalkvjgh grkrgtt      usmjtsrkrsl@xyz.com   \n",
       "1       2  cksmrsnsljkhsnv     hfkgyrgn gljkhgnlz  cksmrsnsljkhsnv@xyz.com   \n",
       "2       3        ahjmsnshe    hrHJYGNGHH DKBHGLzg        ahjmsnshe@xyz.com   \n",
       "3       4        skhldrrpu      yskuldrrf kuygrgo        skhldrrpu@xyz.com   \n",
       "4       5      zbhhprndrsm  kkbhufrndrg whguhgniy      zbhhprndrsm@xyz.com   \n",
       "\n",
       "   Alloted Set  Total Score  Section1  Wrong Answers 1  Marks 1  Section2  \\\n",
       "0            1           34        25               12       13        25   \n",
       "1            1           32        25               16        9        25   \n",
       "2            1           34        25               17        8        25   \n",
       "3            1           27        19               10        9        15   \n",
       "4            1           35        25               13       12        17   \n",
       "\n",
       "    ...     Marks 2  Section3  Wrong Answers 3  Marks 3  Section4  \\\n",
       "0   ...           5      15.0             11.0      4.0      10.0   \n",
       "1   ...           5      15.0             13.0      2.0      10.0   \n",
       "2   ...           5      15.0             10.0      5.0      10.0   \n",
       "3   ...           4      13.0              9.0      4.0       9.0   \n",
       "4   ...           6      14.0             10.0      4.0      10.0   \n",
       "\n",
       "   Wrong Answers 4  Marks 4  Section5  Wrong Answers 5  Marks 5  \n",
       "0              9.0      1.0      25.0             14.0     11.0  \n",
       "1              7.0      3.0      25.0             12.0     13.0  \n",
       "2              7.0      3.0      25.0             12.0     13.0  \n",
       "3              9.0      0.0      20.0             10.0     10.0  \n",
       "4              7.0      3.0      24.0             14.0     10.0  \n",
       
