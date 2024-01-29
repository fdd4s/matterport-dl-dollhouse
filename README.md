# matterport downloader dollhouse

## What it does

matterport-dl-dollhouse downloads dollhouse 3d model of Matterport houses

## Dependencies

php, php-curl, curl  

This code can run over Linux and Windows  

## Usage

    $ php ./matterport-dl-dollhouse.php <matterport id>  

e.g: If the url is https://my.matterport.com/show/?m=huhpm6maGbT&mls=1 you have to run the script this way:  

    $ php ./matterport-dl-dollhouse.php huhpm6maGbT  
    
it will download .dam file and .jpg texture files, then use  
https://github.com/codespacehelp/matterport-decoder  
or  
https://github.com/willowpsychology/rogue_matterport_archiver  
To convert .dam file to .obj file

## Viewers

.obj result file can be opened with Blender https://www.blender.org/ (File...Import...Wavefront (.obj))

## Credits

Created by fdd4s  
Send feedback and questions to fc1471789@gmail.com  
All files are public domain https://unlicense.org/  
