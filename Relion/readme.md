# Watch Youtube video of Grant Jensen's cryo-EM course  
&nbsp; &nbsp; &nbsp; &nbsp; Dr. Grant Jensen from Caltech gave this excellent series course of cryo-EM, starting from its principles to sample preparation, to data processing. It is not too mathy, but it still gives a good illustration of the theoretical principles. Electric engineering courses like *__Signals and Systems__*, physics courses like *__Optics__*, and machine learning basis would help with the understanding of mechanical and processing details.  
&nbsp; &nbsp; &nbsp; &nbsp; Videos can be found in this link: [https://jensenlab.caltech.edu/courses/] from a variety of sources (Coursera, Youtube etc).

# Use Relion to process the micrograph data  

## A quick start from tutorial  
  The Relion tutorial is the quickest way to kick away cryo-EM micrograph processing, which can be downloaded here [https://hpc.nih.gov/apps/RELION/relion30_tutorial.pdf]. Working through all the steps as much as you can will bring you closer to this encryptic cryo-EM data processing. For me I used Relion 3.0.5, while this tutorial is for Relion 3.0, there is some discrepency between the software GUI and the tutorial.  
  
  There are certain features of the Relion 3.0 tutorial that I would like you to know before starting:  
- **Alwalys hold on to click "Run" button. Wait!**  
As lines later you would find it says "it may be a good idea to give this job an alias like LoG_based" while you have runshed to run it with default 'job37'. This is not a big deal in term of the results, since it's only about naming. But it can impair your follow-up with the tutorial, as you may have different names for the files.

- **Manual picking of the default dataset**  
When first staring at a micrograph during manual picking process, you might have no idea what to select from a vague Moorse graph. The points here are i) select the dark color particles; ii) select them in areas that they each separate from others. 

- **What are good particle classes?**  
I give the following example of good and bad particles. They can impact the 'Initial model' result. My first attempt ended up with a bolb with no features. The initial model does not need to be perfect, but it should have some features. 
