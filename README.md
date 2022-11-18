# Metadata of an Acoustic Monitoring Project
## Sounds of the Rainforest
![40-of-the-amazon-rainforest-is-at-tipping-point-to-becoming-savanna-341236-1280x720](https://user-images.githubusercontent.com/61201657/202615382-f9ff45d3-5827-4fea-9374-6537991a5694.jpg)
img_source: https://assets.technologynetworks.com/production/dynamic/images/content/341236/40-of-the-amazon-rainforest-is-at-tipping-point-to-becoming-savanna-341236-1280x720.jpg?cb=10921432

Tropical forests are the world's most biodiverse ecosystems, supporting and providing a home to thousands of animal and plant species. For scientists studying the effects of human pressures on ecosystem health, and in order to ensure the protection of rare species, it is necessary to keep track of the wildlife that lives in these regions.

Biodiversity monitoring has been commonly done manually by highly trained professionals who have the skills to recognize animals in the forest by sight or sound. Over a time period of months or years, a dataset of all the animals observed at a specific location in the forest can be compiled. Even though this is an established and tested procedure, it is costly, time consuming, and prone to human bias.

SAFE Acoustics is an interdisciplinary research project in which cutting-edge engineering and machine learning developments are used to fully automate biodiversity monitoring in Borneo's tropical forests. This is done by listening to the animals' sounds.

At the SAFE project research site in Sabah, Malaysia, they created real-time acoustic monitoring units and have deployed them in a network across varied levels of forest degradation. Some of their recorders are located in primary forest that has been greatly unaffected by humans, whereas others are located in logged forests and even in commercial oil-palm plantations.

source: http://acoustics.safeproject.net/about

## Exploratory Data Analysis of SAFE acoustic monitoring dataset

"This dataset contains a series of 20 minute avifaunal and herpetofaunal point counts conducted throughout the SAFE landscape across a land degradation gradient. Point counts were spread evenly throughout the 24 hours of the day. Associated with each point count is an audio recording file, so (theoretically) this could be used as a training dataset for automated bioacoustic studies. Jani Sleutel was responsible for avifaunal surveys and Adi Shabrani / Nursyamin Zulkifli for herpetofaunal data. This experiment was primarily designed by Sarab Sethi and Rob Ewers as part of the WWF Biome Health project."

The data was collected by installing prototype hardware systems(consisting of a Raspberry Pi, an electret microphone, an external audio card, a 3G data dongle, a solar panel and a battery) in the forest at Maliau (Sabah, Malaysia) and at SAFE. Microphones were installed in the tree canopy, using poles to extend the solar panel arrays beyond the shade of the canopy and ensuring continuous charging. Using lower quality audio allowed them to make use of slower mobile internet connections as well as reducing overall battery consumption of the system. They selected sites that had adequate mobile coverage. Acoustic data was transferred to servers in the UK via the mobile network. Celcom was used for data transfers, as previous field trials have demonstrated a consistent upload speed of > 1 Mbps can be achieved from ridges and south facing slopes. They expected to install up to 15 microphones to provide continuous acoustic data from sites that vary in terms of historical logging intensity and in future forest fragments that vary in size from one to 100 ha.

sources: https://www.zenodo.org/record/3997172#.Yj7Xu-fMI2z, https://www.safeproject.net/projects/project_view/175

#### My initial plans for this project was to explore the data to determine if birds sing differently in different locations. However, upon reaching the audio analysis part to answer the question, I've come to realize how noisy the audio files of the dataset are and how difficult it would be to analyze them. There were so many birds of different species singing in each audio file with lots of noises that it was at times difficult to spot where the bird I was analyzing was recorded in the file; and when it was spotted, the audio was only a couple seconds long so I didn't have much to work with. 
#### As a result, this project no longer tries to answer whether birds sing differently in different locations. Instead, this project is an exploratory data analysis project that will explore the metadata, look for patterns in it, and try to summarize and represent them.
