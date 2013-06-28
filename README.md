
=======
wp7dlls
=======
how to use this:
1. copy your rom(.bin file), to tools folder;
2. open cmd prompt;
3. to dump the content of a .bin:
	viewbin.exe FILENAME.bin
	write down start and length
	cvrtbin -r -a START -w 32 -l LENGTH FILENAME.bin
	this command converts the FILENAME.bin to a FILENAME.nb0 (START and LENGTH from the command bevor)
	dumprom.exe -d dump -v -5 FILENAME.nb0
	the content of the FILENAME.bin will be written in the directory "dump". It must exists, otherwise an error occurs.



from: http://www.t-hack.com/wiki/index.php/NK.BIN_toolset