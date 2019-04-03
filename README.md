# R visualizations

This is a beginner tutorial on using R for beautiful visualizations

# Setup

Navigate to rc.uab.edu in your preferred web browser and login. 

From the dashboard, click "Jobs" and then "Job Composer" to open the job composer.

Create a new job from the default template. Then scroll down the page and select "Open Editor" at the bottom under "Submit Script"

Copy and paste the following code into the editor window. (Replace all current code with the pasted code)
```
#!/bin/bash
# JOB HEADERS HERE

git clone https://gitlab.rc.uab.edu/rc-training-sessions/r-visualizations.git /data/user/$USER/r-visualizations
```

# Start RStudio
Launch RStudio through the interactive apps page in the OnDemand (rc.uab.edu) portal

Use the following command within RStudio to move the working directory to the downloaded repository

Please note, within R, the environment variable "$USER" is not mapped, so  replace $USER with your actual blazerid

```
setwd("/data/user/$USER/r-visualizations")
```

