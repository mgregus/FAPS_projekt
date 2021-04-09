# FAPS_projekt

This project has used tool stegano to hide data inside a .png pictures using the LSB method. Then the created stego objects have been submitted to steganalysis using tools such as Zsteg, Stegoveritas, Steg and StegoOnline. In the file stegano.txt are explained basic commands and use cases which have been used to hide the data and messages inside the cover images. 
From zsteg -a option has been used
From stegoveritas - exif, extractLSB, bruteLSB, exif and carve have been used
From stegonline - show RGBAvalues, extract files have been used

#### stegoobjects
contains the created stego objects(the imamges with hidden inforamation)
generators used: _er - eratosthenes, _id - identity, _cm composite, 
data embeddes: _ms - message, _sa - short alice in wonderland, _al - alice in wonderland, vlozenepdf - pdf subor, _slm - vlozena fotografia 

#### vkladane_spravy
contains text files hidden, image hidden and the pdf hidden

#### stegoveritas
contains results of either imageTrasnfer or brute-LSB or exif or carve methods of tool Stegoveritas applied on the stegobjects, where metadata for the given image or image transfers with enahnced lsbs can be vieved

### modifikovane
contains modified stego objects 

#### screenshots
contains screenshots taken while working with the tools

#### lsbenhanced
contains lsbenhanced versions of given stegoobjects to provide an example how visible irregularities in the lsb values can be analysed, along with how usage of generators can diminish or hide those visible irregularities completely

#### povodne_obrazky
contains original images which have been used as cover images
