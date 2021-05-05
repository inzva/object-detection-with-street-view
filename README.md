# inzva: AI PROJECTS #6 FOR SOCIAL GOOD

This is the repository for inzva AI Projects for Social Good #6 project - Object Detection with Street View Images for Demographic Analysis. Our project is inspired from the study conducted in [Stanford University](https://news.stanford.edu/2017/11/28/neighborhoods-cars-indicate-political-leanings/) and aims to replica the study in Istanbul using Google Street View (GSV) images. The study aims to extract insights from GSV images by using object detection in order to predict development level of the neighbourhoods.

For more details about the project you can refer to inzva's blog(-Blog post to be added)

We used [Social-Economic Welfare Level Index (SEGE)](https://kisi.deu.edu.tr/yunusemre.ozer/lce_sege-2017.pdf) developed by Ministry of Industry and Technology of Turkey as our target dataset to use as a benchmark for development level of the district in Istanbul.  SEGE uses several features such as population, health and education accesses and economic levels to determine development level.

To do this, we developed a way to get images from each neighbourhood using Haversine Distance and acquired images (approximately 250 images each) for 10 different districts of Istanbul. After that using [imageAI](https://github.com/OlafenwaMoses/ImageAI/tree/master/imageai/Detection) library, we predicted objects in those districts and check whether is there any correlation between number of objects in each district and their SEGE score.

In this repository you can find the notebooks on acquiring data from Google Street View API, object detection via ImageAI library and our final presentation that is made at [AI Projects #6](https://inzva.com/2021/ai/projects/ai-project-group-6-social-good)

Contributors Github pages:

[Alara Hergün](https://github.com/alarahergun)

Başak Ekinci

[Efehan Danışman](https://github.com/efehandanisman)

[Sefa Kurtipek](https://github.com/sefakurtipek)
