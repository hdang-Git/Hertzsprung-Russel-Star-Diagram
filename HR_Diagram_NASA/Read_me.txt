This is a small test project reading data from NASA to display a HR Diagram

Hertzsprung–Russell Diagram

This is a scatter plot that helps show the relationship between star's 
absolute magnitudes and luminosity vs the spectrum and temperature (Stefan-Boltzman Law)

to run and test the program:

1. open HR_Diagram.jar
2. hit [Upload Data] Button
3. find the "stardata.txt" file in the [data] folder of project.
		(a hyperlink of the source is in the program)
4. hit [ok] and watch the program populate with data.

feel free to select any amount of stars on table on the right.



[add star] fill out all text box and then click "Add Star" button.

[edit line] select star in the table, hit "edit line" button. then make following changes under Add (Edit) Star. then hit [add star] button.
NOTE: Be sure to not change the Hip Number(XXX) textbox.

[Remove Star] select star in the table and hit "remove star" button to delete.

[Save Data]: Hit save data and give name to file and save.
Note: extension .txt not necessary.

[Upload Data]: Click "Upload data" button and select file and open the file and it should populate the table and plot the points.
NOTE: the file should be in the following format.

	Hip	V	RA (deg)	Dec (deg)	Par(mas)	B-V	M_V	Sp
	38	8.65	0.11104694	-79.06183133	23.84	0.78	5.54	G6V
	57	8.27	0.16828557	-69.67580068	33.89	0.86	5.92	K2V
	58	7.05	0.17376341	62.17600484	26.06	0.52	4.13	G0
	128	6.5	0.41376473	73.61187664	15.2	0.18	2.41	Am...



(future possible changes)  store information into a database,
and compare the v-magnitude and v-apparent and toggle both to see a comparison 