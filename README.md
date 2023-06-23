### Analysis of Micturition readings
Provided here is a method to analyse micturition readings obtained from a LoggerPro connected to weigh scales or other measurement device. 

This method will allow you to take something like this: 

![image](https://github.com/kjaitken/Micturition_readings/assets/13381429/a8ee7988-f660-4593-be24-b2e530d64acc)

and turn it into useable data like this: 
![image](https://github.com/kjaitken/Micturition_readings/assets/13381429/43a73541-70d0-4abe-9141-d5bb4eaed1ef)

The data here available for trial here is 'dummy' data which can be replaced with your own. 
Adjust the threshold of detection and the small voids threshold according to the distribution in your species, strain and age. Additionally, use of this with mouse data requires additional filtering due to the presence of solid material. Additional python code will be placed on this site for mouse data, but the original for the mouse data is from Martin Sidler's publications and script:  
Sidler, M., Aitken, K. J., Forward, S., Vitkin, A., & Bagli, D. J. (2018). Non-invasive voiding assessment in conscious mice. Bladder, 5(2), e33. https://doi.org/10.14440/bladder.2018.582  DOI https://doi.org/10.14440/bladder.2018.582
https://www.sciencedirect.com/science/article/abs/pii/S0090429517302959
https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5565093/

The python file can be found here: https://github.com/kjaitken/Micturition_readings/blob/main/rat_voiding9.ipynb

Input data should be in csv format with time in minutes in column 1, then further columns as many as needed, for your data. For our experimental use, standard numbers of columns covered 11 hours, with the first 30-60 minutes removed as the system settled. If measurements are more than once per minute, a conversion factor will be needed to convert to 1 minute. This is included in a commented out section as it is not always needed.  

Please reference this repository and me and Martin in your methods!
Any questions or queries: you can find me at the DIYBio/ HackLab Toronto and karen.aitken@alumni.utoronto.ca. 
Previous work was performed at the Hospital for Sick Children under Dr. DJ Bagli. 
