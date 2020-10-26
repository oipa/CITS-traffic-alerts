# CITS traffic alerts

This repository includes two different image datasets that were created to develop a traffic sign recognition system and  a fog detection system.

## Ceit - TSR 
  Ceit Traffic Sign Recognition database consist of 264 images captured from 40 differentvideos of driving tracks within the Basque Country (Spain). They were recorded using different mobile phone and on-board cameras located on the dashboard. These images were specifically selected to cover several challenging conditions:
  - Shadows
  - Dawn/dusk
  - Motion blur
  - Bad weather conditions (fog, rain)
  - Distant signs
  - Low contrast
  - Whidshield artefacts (reflections, raindrops, dirtiness)
  
  It contains 418 bounding boxes that were also annotated (Image Labeler - Matlab) in 6 different categories: 
  - speed-limit
  - prohibitory
  - mandatory
  - caution
  - yield
  - restriction ends
  
  ![alt text](https://github.com/oipa/CITS-traffic-alerts/blob/main/Ceit-TSR-dataset.jpg?raw=true)
  
  *If you are going to use this dataset please cite our paper ....*
  
  ## Ceit - Foggy 
  Ceit-Foggy database consists of a set of 41 videos corresponding to approximately 300 km of driving through the Basque Country and Segovia (Spain). In total 4480 frames have been extracted and labelled in 5 categories depending on the general weather condition: 
  - sunny 
  - cloudy
  - light fog 
  - moderate fog  
  - dense fog
  
  Additionally, in some videos, if there was also rain or it was a dawn/dusk, this has also been specified. As for Ceit-TSR database, these images were also recorded using different mobile phone and on-board cameras located on the dashboard. It is worth mentioning that these annotations just classify the general condition of the images, however, especially for long tracks, these conditions could change during the video.
  
   ![alt text](https://github.com/oipa/CITS-traffic-alerts/blob/main/Ceit-Foggy-dataset.png?raw=true)
  
   *If you are going to use this dataset please cite our paper ....*
