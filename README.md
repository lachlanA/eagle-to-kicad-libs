###**Convert Eagle to KiCad lib's.**


* This **ulp** (*Eagle user script file*) along with one include file will convert a **Eagle** *lbr's* version file to a **KiCad** *lib/mod* file.  

* This is part of the Eagle SCH/PCB to KiCad SCH/PCB conversion project hosted at https://github.com/lachlanA/eagle-to-kicad  

* The main purpose of the extra doc's is not to over load the user with extra information about SCH/PCB conversion, when they only need to convert a Eagle *LBR* to KiCad.  
	* Note: If you wish to do Eagle SCH and PCB conversion, and also extract KiCad lib from the Eagle SCH/PCB files, or you don't have access to the Eagle lbr's, and need to extract them, please see https://github.com/lachlanA/eagle-to-kicad for the *ulp* which will do full conversion of SCH/PCB to KiCad  

* Notes: 1: This ULP will only build KiCad *lib/mod* from Eagle *lbr* file. It will not build project files for KiCad or configure the library setup for KiCad. You will need to nanualy do this in KiCad.  

* The freeware version of Eagle has no limit on the size of the libary you can convert to KiCad lib/mod. You can get ealge from here:  [Eagle](http://www.cadsoftusa.com/download-eagle/).  And KiCad beta for Windows from here: [Windows-xp,7,8,10](http://downloads.kicad-pcb.org/windows/).  And finaly all other versions of [KiCad](http://kicad-pcb.org/download/)

* A number of example's of converted Eagle lib's have been provided in the *examples* directory if you wish a Eagle *LBR* file to be added to this *examples* please contact me.  
    Note: only public domain Eagle *lbr* will be added to the *examples* director.  
###Installing.
* Download the zip file, (*click on the Button to the your bottom right on this page*. **Download ZIP**) And unzip using your favorite zip program to your target directory. *OR* if your prefer git

			git clone https://github.com/lachlanA/eagle-to-kicad-libs.git  

* ***eagle-lbr2kicad-1.0.ulp***...............  Convert Eagle lbr to KiCad lib/mod  
* ***eagle_to_kicad_include.inc*** ........  Include file used above *ulp* ULP's  
####HOW TO RUN THE ULP'S 
 
 **WARNING Always backup your Eagle SCH/PCB/LBR files before running this program!**  
 
* **1:** Start your Eagle program *(Make sure your using  version 6.xx or above Eagle)*

* **2:** Open the Eagle *LBR* file you wish to convert.

* **3:** Next Open the top left hand  **File menu** and select  **Run ULP**  

* **4:** A file requester window will open.  Using this, to select,find,or type the location of the ***eagle-lbr2kicad-1.0.ulp*** ULP you download from this website.

* The ***eagle-lbr2kicad-1.0.ulp*** window will open with a number of options. Just select OK for the moment.  And if *Murphy's Law  is sound asleep* we should have the target directory with the new KiCad *lib* and *mod* files.
* NOTE: The converted files will be KiCad old format, and will be converted to the new format, when you first save them from KiCad.



* **NOTE'S:**   For more info on [KiCad](http://www.kicad-pcb.org/display/KICAD/Installing+KiCad)  
As KiCad is the process of major upgrade,  and enhancement  please be nice asking ? of the Development team.  I think you  will love the new Push and Shove router, that feature alone make's it worth while moving from Eagle to KiCad I hope the ULP's  make the job a lot easy.




  

