
# Commander X16 Function key mapper  

A BASLOAD program to re-map the X16 function keys.  
** See the RELEASE folder for needed files.  **  
Free to use and modify for whatever.  

## How to use - about  

FKM.BL is a BASLOAD program to remap the x16 function keys.  

to use:  
1 - Use the x16 editor to load the FKM.BL code so you can change the function keys. Type 'EDIT "FKM.BL"'  

2 - Edit the code to remap the function keys  
	
	REM --- SET KEYS YOU WANT TO CHANGE (!!!10 CHAR MAX!!!)  
	NEW.KEYS$(1) = "BASLOAD" + CHR$(34)  
	NEW.KEYS$(2) = "I.B" + CHR$(34) + ":RUN:" + CHR$(13)  
	REM NEW.KEYS$(3)  
	REM NEW.KEYS$(4)  
	REM NEW.KEYS$(5)  
	REM NEW.KEYS$(6)  
	REM NEW.KEYS$(7)  
	NEW.KEYS$(8) = "/FM.PRG" + CHR$(13)  

	In the code above only function keys 1,2 and 8 will be remapped.  

3 - When done save your work and exit the editor.  
4 - Run 'BASLOAD FKM.BL' -- this will create a .prg executable in memory.  
5 - Type 'SAVE "@:FKM.PRG",8' to save to disk  
6 - Type 'RUN' and FKM.PRG will run and remap your new function keys.  
 
## Notes 
The BAT files are just my way of running the X16 Emulator.  

