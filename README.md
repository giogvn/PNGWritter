# PNGWritter
A Python class to write text in PNG files

## Contents
 1. Use cases
 2. Features
 3. How to use

### 1. Use Cases
#### 1.1 Optical Character Recognition (OCR) Testing
Ideal for developers that need PNGs files to text an OCR system with some domain specific text in it. Just provide the path of your PNG files, the domain specific entities your text must cover and you're done.

### 2. Features
#### 2.1 PNG files selection
The files one wishes to write text into can be randomly sampled among files contained in a path or user-defined. Is the later is your wish, just provide the names of the files you wish to use and you're done. More details in the Files Selection section ahead.

#### 2.2 Text Selection

The current text entities the PNGWritter class is capable of writing are the following:
 - Age (AGE)
 - Person Name (PERSON)
 - Date (DATE)
 - Sex (SEX)
 - Organization (ORG)
   
Moreover, the class is also capable of writing random sequence of characters in the PNG files. More details on how to choose among such entities (or randomly select a subset of them) in the How-to-Use section ahead. 

#### 2.3 Font Selection

##### 2.3.1 Font Files

The fonts TTF files used to write the text in the PNGs can be sampled from all the ones contained in the user-defined path for such TTFs or be sampled from a subset of such files.   

##### 2.3.2 Font Colors

The font colors can be defined in the following ways:
- High contrast with the background of the image's region being written (default)
- Low contrast with the background of the image's region being written
- User-defined

#### 2.4 Outliers Generation

We consider two outliers categories:

- Color Outliers: the font color used to write in the images do not have a high contrast with the background of the region being written
- Position Outlier: the text written is not on the header or footer positions of the image

More details on the How-to-Use section ahead.

#### 2.5 Layout Drawing
it is possible to draw a header or a footer in some proportion of the PNG files being written. A layout can be a header or a footer.



