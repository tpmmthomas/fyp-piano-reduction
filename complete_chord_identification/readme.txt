The key code is in pipeline.ipynb

The running environment is specified in requirements.txt

Python 3.6 is used

-----------------------------------------------

Function: total_inference_midi
Input: 		midi file

Return: 	list of pair
			pair: [[start_tick, end_tick], predicted_chord]

		
		csv file 
			located at ./output folder

how to use:	chordify_midi = total_inference_midi("path_to_midi_file") 
