# Esel smoothing parameters

Purpose	
1	Test the impact of modifying the smoothing parameters 
2	See the effect of adding „descent facor“ as a further smoothing parameter 
	which in cases of falling blood sugar will draw the smoothed values down towards the raw data. 
	This helps to avoid excessive insulin dosing due to otherwise overestimating blood sugar values.
	
	
Usage	
	Modify the smoothing factors in sheet „1st_Result“ (yellow cells) and watch how the green curve changes immediately.
	This way you can draw your own conclusions which set of smoothing facors fits your needs.
	Hint: if you have a large monitor (or 2 of them) you can display both tabs simultaneously and see the effect on both.
	
	When you import your own data into columns A-F be carefull to only overwrite original data
	do not insert/delete columns as that may destroy formula references.
	
	
Tab „1st_Result“	
	Shows 3.5 hours of real world data covering the early evening
	- sensor data are the raw values from Eversense
	- smoothed data as output at the time by ESEL with default parameter settings
	- downward esel shows the potential extension of smooth to include the descent factor impact
	
	
Tab „2nd_Result“	
	Shows 9 hours of real world data covering the night and early morning
	- graphs and colors as described above
