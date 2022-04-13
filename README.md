# Cognitive-Aware-Lecture-Video-Recommendation-System-using-Brain-Signal-in-Learning-Pedagogy
Code and Single-channel EEG Dateset:

Steps: i) First you executed the code File_trim_6sec.ipynb : This code trim first and last six second data and create one, two, three window size dataset.
		You can noted that:
	   		 a) Dataset path and name.
	    
	ii) Next you executed the code Withcluster.ipynb : This code for clustering the data using kmeans or bisecting_kmeans and calcutting the attention of the video for each student.
		You can noted that:
    			a) algorithm = kmeans or bisecting_kmeans
    			b) Dataset path and name.
    			c) CSV file name where you save the output (video attention value).
        iii) Next you executed the code IntRec.ipynb : This code find the attention of the video for each student using without clastring.
	iv) Next you executed the code NDCG.ipynb : Using this code you find out the NDCG.
	iv) Next you executed the code Recall_precision.ipynb : Using this code you find out the Recall, Precision, and F1 value.

Contact: 
If you have any questions, feel free to open an issue or contact Rabi Shaw (shaw.rabi@gmail.com).
