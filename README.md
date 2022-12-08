# Outlier detection techniques applied to the Ionosphere dataset.

In this report, we studied a sample of data called “Ionosphere”, which contains radar data that was collected by a system in Goose Bay, Labrador Canada. The system consists of a phased array of several high frequency antennas with a power total emitted of around 6.4 kilowatts. The targets were free electrons in the ionosphere. Good (classified “g”) radar returns are those that highlight a certain type of structure in the ionosphere. Bad ("b" for bad) returns are those that don't; their signals pass through the ionosphere.

The sample contains 351 observations and 33 variables, including the “class” variable which is the one that we seek to explain. The 32 quantitative variables are assumed to be continuous. We are thus faced with a binary classification problem.

The report is structured as follows: first, it is a matter of making a statistical analysis of our data sample. Then, we will separate the sample into two groups (train and test) and build and optimiaz random forest models for classification.

After that, we built and tested an isolation forest model for anomaly detection. We then perform the principal component analysis (PCA) of the data studied its use in the reduction of the number of variables as well as in anomaly detection. Finally, we implemented the descriptive and predictive LDA in order to discriminate between the two classes “g” and “b” of individuals, as well as to isolate outliers under certain conditions.
