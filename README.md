# 659airbnb

Draft 1 explored data set, set up initial model for price optimization. Found reasonable but not acceptable MAE, RSME, and R2

Draft 2 created variables to further break down numerical data, like price per bed. This gave much stronger MAE, RSME, and R2 vaues

Draft 3 piloted model options for price optimization. Initially random forest was used, but it was shifted to elastic net. Initial MAE, RMSE, and R2 were acceptable, but could be further optimized. 

Draft 4 offered commentary and room for improvement for price optimization. Started market segmentation section, requires clustering which we have not covered in class, but found old slides/readings (linked in draft 4 lines 342-351). Did not evaluate if good fit. 

Draft 5 restructured code for market segmentation, and introduced further segmentation models focusing on amentities and location at attempt to improve silhouette scores. At this time, cluster_config is uploaded. 

Cluster config is the running doc where code related to clustering is edited before being pasted in the next draft of the full project. Created because there are hundreds of lines and 30+ datasets created to produce the plots and trying to adjust values in the primary document is going to get messy. 
