Manage the data available in the WebCox app. Load data into memory, Save data to disk, or Remove a dataset from memory.

#### Load data

The best way to get data in and out of WebCox (and R) is to use the R-data format (.rda). These are binary files that can be stored compactly and that can be read into R quickly. Choose the .rda radio button and click 'Choose file' to locate the file you want to load on your computer.

Loading data from Excel can be achieved in two ways. First, you can save data from excel to a csv format and then, in WebCox, choose the .csv radio button. Most likely you will have a header row in the csv file for variable names. If the data are now comma separated you can choose a semicolon or tab separated format. Then click 'Choose file' and locate the csv file you created in Excel on your computer. 

Alternatively, you can copy the data Excel (i.e., CTRL-C on windows or CMD-C on mac) then go to WebCox and choose the clipboard button and then click the 'Paste data' button. This is a short-cut that can be convenient for smaller datasets that are cleanly formatted. If you get an error here try saving the data to a csv format and loading it into WebCox as described above.

To get access to all the data files bundled with the WebCox app choose the examples radio button and click 'Load examples'. These files are used as illustrations of the various analysis tools included with WebCox. For example, the catalog data is used to demonstrate regression (i.e., Regression > Linear (OLS)).

#### Save data

As mentioned above, the best way to get data in and out of WebCox (and R) is to use the R-data format (.rda). Choose the .rda radio button and click the Save data button to store the data on your computer. 

It is good practice to add a description of the data to each file you use. For the files that are part of WebCox you will see a brief overview of the variables etc. below the table view of the first 10 rows of the data. If you would like to add such a description check the 'Add/edit data description' check-box. A window will open where you can add text in <a href="http://support.iawriter.com/help/kb/general-questions/markdown-syntax-reference-guide" target="_blank">Markdown</a> format. The descriptions of the data included with WebCox should serve as a good starting point. 

Saving data from WebCox for use in Excel can again be achieved in two ways. First, you can save data to a csv format and load it into Excel (i.e., choose the .csv radio button and click 'Save data'). Alternatively, you can copy the data from WebCox into the clipboard by choosing the clipboard radio button and clicking the 'Copy data' button. In Excel you can then paste the data from WebCox into a worksheet (i.e., use CTRL-V on windows or CMD-V on mac). 

#### Remove data from memory

If there are data you no longer need access to in WebCox you can select them and click the 'Remove data' button. One datafile will always remain open.

&copy; WebCox (2014) <a rel="license" href="http://creativecommons.org/licenses/by-nc-sa/4.0/" target="_blank"><img alt="Creative Commons License" style="border-width:0" src="http://i.creativecommons.org/l/by-nc-sa/4.0/80x15.png" /></a>

WebCox included and modified the source codes of Radiant.