--------------------------------------------------------------------------------
# NTag (audio file tag editor)
--------------------------------------------------------------------------------

Main features: 
-------------------
  - Viewing and editing tags in audio files
  - Supported tag fields: title, artist, album, track, disc, year, date, comment, composer, album artist, language, lyrics, genre, compilation
  - Supported audio formats: MP3, MP4 (M4A, M4B), FLAC, OGG and WMA
  - Supported tag formats: ID3v1.1, ID3v2.3, ID3v2.4, MP4, ASF, APE and Vorbis Comment
  - Batch editing of multiple files  
  - Supported Cover Artwork formats : JPG, PNG 
  - Resize/Shrink Cover Artwork
  - Rename files based on the tag information
  - Filter files by Missing Artwork/Lyrics/Metadata
  - Portable Java App
  
System Requirements :
----------------------

 - 250MB of free RAM
 - Java Runtime Enviroment (JRE) 8

This distribution contains the following files:
-------------------------------------------------

```
   history.txt                - History of NTag
   license.txt                - License information
   readme.txt                 - This file
   tag_mapping.pdf            - Tag mapping documentation   
   libs/jaudiotagger-*.jar    - Jaudiotagger Tagging library 
   ntag.jar                   - Executable Java program   
   
Tag-Editor

   ntag.exe                   - Windows executable (jar wrapper)   
   ntag.ini                   - Configuration file
   ntag_logging.properties    - Logging and Debug settings
```

Launch from command line:
--------------------------

```
javaw -jar ntag.jar ntag.NTag
```

Project Web site :
--------------------

https://github.com/nrittsti/ntag/

--------------------------------------------------------------------------------
Licence:
--------------------------------------------------------------------------------

NTag is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

NTag is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with NTag.  If not, see <http://www.gnu.org/licenses/>.

Copyright 2017, Nico Rittstieg

--------------------------------------------------------------------------------
Third party libraries used by NTag
--------------------------------------------------------------------------------

Nuvola Icon Theme
Autor:   David Vignoni
Licence: LGPL

JAudiotagger Library 2.2.4
Autor:   http://www.jthink.net/jaudiotagger/
Licence: LGPL

--------------------------------------------------------------------------------
End of document
