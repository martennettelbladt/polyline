# polyline

A monospaced 3×5 vector typeface designed by Mårten Nettelbladt in October 2014 and finalised in May 2018.
The .shx file is a native AutoCAD font file and should be placed in the Fonts folder of the AutoCAD installation.
For example here: C:\Program Files\Autodesk\AutoCAD LT 2020\Fonts

More info: http://martennettelbladt.se/polyline

The .shp file can be edited in an editor like Notepad++.
Shapes of the letters are defined as coordinates.
The .shx file is a compiled version of the .shp file.
To compile an .shp file you need a full version of AutoCAD, use the "Compile" command.

/Mårten

; --------------------------------------
; * = start of character definition
; 04D = unicode number
; 21 = number of bits in definition
;
; 0 = end of character definition
; 1 = pen down
; 2 = pen up
; 5 = store position (to stack)
; 6 = get position (from stack)
; 7 = insert character (unicode)
; 8 = move one vector
; 9 = move series of vectors
;
; (10,20) = vector coordinates
; (0,0) = end of vector series
;
; nbsp = non-breaking space
; shy = soft hyphen
; 
; --------------------------------------
