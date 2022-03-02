# Linear Dimensionality Comparison of Stimulus-Response Pairs

This project was completed as a Capstone for the 2020 Neuromatch Computational Neuroscience Summer School, a program focused on using computational modeling and machine learning to understand neural and behavioral data. For this project, I proposed to my group a project that used Principal Component Analyses (PCAs) on data from this paper(<https://www.nature.com/articles/s41586-019-1787-x>) 

This paper has mice doing a simple two-choice decision-making task while activity from neurons across a wide variety of brain areas. By using individual PCAs on massive amounts of data within each brain region and at different points during the decision-making process we could compare how high-dimensional these signals were up to a standard threshold of variability explained across regions and time points. This allowed us to make the number of Principal Components our primary outcome variable we were measuring. Literally allowinf us to compare how high-dimensional, and potentially informative each regions signal was at different points in the decision making process.

The project was completed using a Jupyter Notebook and coded in Python. The analyses and visuals were created over the course of a week and a half by each member of the group.

Here is my video presentation I did to present the project to the NeuroMatch Summer School, <https://youtu.be/UK9wnWyZxt8> (15 minutes)

## Sample Results

### Linear Dimensionality of the Forebrain's Neural Signal During Different Decision Types
![ForebrainPCA](https://user-images.githubusercontent.com/7660406/156463850-b9aea573-7ab7-4aaf-9ea5-6a036cd217f9.png)

![This figure shows how Linear Dimensionality changed across different decisions, those in which the mouse chose the correct response(hit), when they chose the wrong response (miss_wrongSide), and when they did not respond (miss_nogo). We calculate these seperately for whether the stimulus was presented on the left or right. We can see that the dimensionality was highest for the hits, this goes along with the idea of the forebrain being important in making good decisions. We can also see that Dimensionality varies widely when the mice did not respond, this supports the idea that mice could omit a response for several reasons, either not engaging with the task (where we would guess the dimensionality to be low) or from deliberation in their decision (where we would expect it to be higher).](images/ForebrainPCA.png "Linear Dimensionality of the Forebrain's Neural Signal During Different Decision Types")

### Linear Dimensionality of the Visual Cortex's Neural Signal During Different Decision Types
![VisualCortex](https://user-images.githubusercontent.com/7660406/156463887-4f247b28-cf30-4bc8-b522-7269ceb68938.png)

![This shows the same type of analysis as in the above figure but done on the visual cortex, a region important for processing visual information early on in the process. As you can see it looks quite similar to the forebrain, except the dimensionality is variable across all response types. This also puts a small hitch in the idea that the high dimensionality of the forebrain during correct responses ("hits"), since the visual cortex has it as well. Perhaps the high dimensionality across both regions preceding correct responses actually reflects the whole brain's engagement. When you are focused on getting it right, your whole brain is engaged!](images/VisualCortex.png)

## Contributors

-   Jack-Morgan Mizell
-   Beth Hall
-   Sheri Choi
-   Carolyn Murray
-   Adrienne Terrado
