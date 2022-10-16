EXPLANATIONS FOR THE TABLES OF YNAO HAND DRAWING CATALOGUE

The data sets contain two kinds of txt file. 

*_d.txt : daily information 

Column    	Description
1          	Filename(<Yunan Astronomical Observatory(ynao)>_<sunspot data(sd)>_<date(YYMMDD)>_<time(HHMMSS)UT>_<type of data>_<observatory>_<observer>)
2		        Daily sunspot number(umbra+pore)
3           Daily pore number
4           Daily umbra number
5           Daily penumbra number
6           Daily hole number
7		        Total sunspot areas without solar projection effect (umbra + penumbra+pore) in millionths of the solar hemisphere
8		        Total sunspot areas after correcting solar projection effect (umbra + penumbra+pore) in millionths of the solar hemisphere
9		        Umbra areas without solar projection effect in millionths of the solar hemisphere
10		      Umbra areas after correcting solar projection effect in millionths of the solar hemisphere
11		      Penumbra areas without solar projection effect in millionths of the solar hemisphere
12		      Penumbra areas after correcting solar projection effect in millionths of the solar hemisphere


*.txt: information of each pore, spot, umbra and hole

Column    	Description
1		        Filename(<Yunan Astronomical Observatory(ynao)>_<sunspot data(sd)>_<date(YYMMDD)>_<time(HHMMSS)UT>_<type of data>_<observatory>_<observer>)
2		        Classification of the object (pore, spot, umbra or hole)
3		        X-axis coordinates of the object in units of pixel
4		        Y-axis coordinates of the object in units of pixel
5           The object belongs to which hemisphere
6		        The object area without solar projection effect in millionths of the solar hemisphere
7		        The object area after correcting solar projection effect in millionths of the solar hemisphere
8		        The radius of sun disc in units of pixel 
