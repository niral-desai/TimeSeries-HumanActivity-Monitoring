# TimeSeries-HumanActivity-Monitoring
This repository enables the extraction of time series features from accelerometer data for human activity monitoring using graph-based techniques and permutation entropy and complexity. It provides scatter plots with colored points for different activities and includes sample output tables and instructions. Implemented in Python with NumPy, Pandas.

## Task 1
1. Apply natural visibility graph (NVG) and horizontal visibility graph (HVG) to the
aforementioned data
2. Compute average degree, network diameter, and average path length
3. For the above computations select sample size of 1024 data points ( from 1000
to 2024) for each of the 15 time series
4. Tabulate all the results
5. Generate scatter plots: average degree vs network diameter and color the points
according to walking and running (do this for each accelerometer signal and
each method (HVH and NVG))
6. Generate scatter plots: average degree vs network diameter and color the points
according to climbing up and climbing down (do this for each accelerometer
signal and each method (HVH and NVG))
<img width="638" alt="Screen Shot 2023-05-10 at 12 17 51 PM" src="https://github.com/niral-desai/TimeSeries-HumanActivity-Monitoring/assets/46837140/14b625af-8f03-4f87-82d9-8ff91ededc2f">

##  Task 2
1. Compute permutation entropy and complexity for the aforementioned data.
Consider the accelerometer data in all three directions
2. Vary the following parameters
<img width="652" alt="Screen Shot 2023-05-10 at 12 17 57 PM" src="https://github.com/niral-desai/TimeSeries-HumanActivity-Monitoring/assets/46837140/c966b8ab-c52a-4f9b-ad50-6ec3ae3c57be">


3. Generate scatter plots: permutation entropy vs complexity and color the points
according to walking and running (for signal length =4096, embedded delay = 1,
and embedded dimension = 3, 4, 5, 6, and all three accelerometer directions)
4. Generate scatter plots: permutation entropy vs complexity and color the points
according to climbing up and climbing down (for signal length =4096, embedded
delay = 1, and embedded dimension = 3, 4, 5, 6, all three accelerometer
directions)
<img width="661" alt="Screen Shot 2023-05-10 at 12 18 03 PM" src="https://github.com/niral-desai/TimeSeries-HumanActivity-Monitoring/assets/46837140/e1815b81-968e-46e1-92fa-0c78722be49e">


Disclaimer: I've used only the head and chest dataset for all the activites but you can use others as well I've uploaded the dataset and adding the link as well if anyone need it.
https://www.uni-mannheim.de/dws/research/projects/activity-recognition/#dataset_realworld
Here is the link for the dataset. Ive used  "Dataset-Real World(HAR)2016" for all the 15 subjects.
