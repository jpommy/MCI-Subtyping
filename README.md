# MCI-Subtyping-
Applying community detection-related methods to neuropsychological data

We highly recommend individuals interested in conducting similar analyses should first consult these seminal works and the associated github pages:

Fair et al., was the first to apply community detection algorithms to cognitive data in the context of ADHD, using CD methods based on modularity.  
        # Fair, D. A., Bathula, D., Nikolas, M. A., & Nigg, J. T. (2012). Distinct neuropsychological subgroups in typically developing youth inform heterogeneity in children with ADHD. 
        # Proceedings of the National Academy of Sciences, 109(17), 6769-6774.

Feczko and Fair later utilized hierarchical community detection methods in combination with random forest analyses within ADHD samples.
        # Feczko, E., Fair, D. A., & McWeeney, S. (2020). U.S. Patent Application No. 16/721,512.
        # Feczko, E., & Fair, D. A. (2020). Methods and challenges for assessing heterogeneity. Biological psychiatry, 88(1), 9-17.
        # Feczko, E., Miranda-Dominguez, O., Marr, M., Graham, A. M., Nigg, J. T., & Fair, D. A. (2019). The heterogeneity problem: approaches to identify psychiatric subtypes. Trends in cognitive sciences, 23(7), 584-601.
        
Feczko and Fair have previously provided documentation for the application of community detection methods to neuropsychological data, including infomap.
         # https://github.com/DCAN-Labs/functional-random-forest

Specific to infomap, the code is actively maintained and updated on: 
         # https://www.mapequation.org/infomap/
         # https://github.com/mapequation/infomap
         # That mapequation.org/infomap website provides both an online platform for conducting analyses, as well as, 
         # multiple options for downloading and running the program on one's local machine.

Additional useful scripts used come from the BCT toolbox:    
         # https://sites.google.com/site/bctnet/

First, a brief note on community detection algorithms. As discussed more eloquently and in more detail by others, there are multitude of different community detection algorithms
in existance. We have opted to use hierarchical community detection algorithm based on the map equation available via Infomap (see below).
     # Infomap: Edler, D., Holmgren, A., & Rosvall, M. (2022). The MapEquation software package (Version 2.6.1) [Computer software]. https://mapequation.org

For the sake of replication, we have provided the following scripts/functions that were used in the analyses published in Pommy et al., 2022.

