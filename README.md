# Ripeness Estimation Video Frames
![ripeness-video-dataset](https://user-images.githubusercontent.com/26176656/123220888-09a81680-d4d7-11eb-827f-928bd568c786.png)

Fig. 1. Pictures of grapes taken from a fixed distance, at the same time of the day on (a) August 10, (b) August 14, (c) August 20, and (d) August 25. The color of grapes progressively turns from green to black as the grapes ripen.

Data (i.e., images) of the “Ripeness estimation video frames dataset” is based on a veraison to harvest time lapse video downloaded from the web [1]. The video presents the ripeness stages of a variety of red grapes (Cabernet Sauvignon) demonstrating their change in color from August 10 to August 25, in 13 successive days from a fixed view angle. In all, 13 video snapshots were taken based on illumination criteria so that all the selected images were under similar lighting conditions (Fig.2). Note that both the illumination intensity and the angle between the camera and light source affect the histogram shape, therefore they need to be constant. The images had a resolution of 1920 × 1080 pixels and 24-bit color depth stored in .tiff format. A straightforward approach to describe intensity variations of grapes is a color histogram. Based on grape variety, the green color channel of an RGB image was used to calculate intensity distributions, represented by an IN. Green channel histograms were represented by INs by algorithm distIN [2]. In conclusion, for the 13 selected snapshots of grape ripeness stages, the corresponding INs were induced, provided in “INs from green histograms.xlsx”.


References:

[1] Davis R. (2020) Do grapes change color? understanding grape veraison. [Online]. Available: https://blog.jordanwinery.com/grape-veraison/

[2] Kaburlasos, V.G.; Vrochidou, E.; Lytridis, C.; Papakostas, G.A.; Pachidis, T.; Manios, M.; Mamalis, S.; Merou, T.; Koundouras, 28 S.; Theocharis, S.; et al. Toward Big Data Manipulation for Grape Harvest Time Prediction by Intervals’ Numbers Techniques. 29 In Proceedings of the 2020 International Joint Conference on Neural Networks (IJCNN); IEEE, 2020; pp. 1–6.

Cite as:

C. Bazinas, E. Vrochidou, C. Lytridis, V. G. Kaburlasos, “Time Series of Distributions Forecasting in Agricultural Applications: An Intervals’ Numbers Approach”, 7th International conference on Time Series and Forecasting (ITISE 2021), Gran Canaria, Spain, 19-21 July 2021.
