# Laban Motion-Based Arm Trajectories
A dataset collected to detect qualities of expressivity in robotic arm trajectories. This dataset was released as part of the RA-L paper under review entitled "Can We Automatically Label Expressive Robot Arm Motion Qualities? Open Dataset and Machine Learning Results." Please cite this paper to acknowledge use of the dataset.

This data was collected with two ideas from the study of human movement in mind: Laban Motion Analysis, and especially the subtopic of Laban Efforts. Within the dataset, files are named by <Participant#>_<Condition>.csv, with condition labels being one of 8 specific styles based on the Laban Effort poles: 
- A --> Strong
- B --> Light
- C --> Direct
- D -->Indirect
- E--> Free
- F --> Bound
- G --> Sustained 
- H --> Sudden

## Folder Organization
- **raw_data:** Raw trajectories of robot motion with measured joint positions, velocities, and efforts in an array. 8 Joint values are listed from the end-effector actuators backward to the first joint.     
- **processed_data:** Extracted Features From Raw Trajectories for the reported datasets of LASSO reduced sets for comparisons between most important features across Laban Effort axis.

