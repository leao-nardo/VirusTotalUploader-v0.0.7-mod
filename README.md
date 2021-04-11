this project is based on an older version of this other project https://github.com/SamuelTulach/VirusTotalUploader

I made this because i didnt liked the many changes that were being made on the original so i copied this version v0.0.7 that is the last one that work as i prefer. i see many people also disliked the changes so fell free to use this one and send ideas and pull here too.

In summary, 
this version have the "scan with vt" link in the first menu on mouse right click and not in the "send to" menu
and it checks if the file is already in vt site, if it is, it opens the result in vt withou uploading again (this is my little mod, in the original it asks to result or upload again, so i skipped that to be simpler, faster, more automatic, and to save bandwidth in our pc and vt site , this is good for us and for then, btw its a free service that we use is good to avoid work on there reuploading files that are already there)


# VirusTotal Uploader
![screenshot](https://i.imgur.com/AoYrHye.png)

VirusTotal Uploader is open-source application written in C# and WinForms for uploading files to VirusTotal service. It has a great and simple design with drag and drop interface. It is easy to use and you can avoid many viruses with it!

[![Join the chat at https://gitter.im/VirusTotalUploader/Lobby](https://badges.gitter.im/VirusTotalUploader/Lobby.svg)](https://gitter.im/VirusTotalUploader/Lobby?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge) [![Build status](https://ci.appveyor.com/api/projects/status/ulpfhv1v32bhwaju?svg=true)](https://ci.appveyor.com/project/SamuelTulach/virustotaluploader)



## Warning
This is not officially supported application. It was created, because official VirusTotal desktop app is unmaintained. If you are afraid you can build it from source by yourself. Also please don´t download it from any 3d party sites.


## How to get API key
It is really simple! All you need to do is to go to [VirusTotal official page](https://www.virustotal.com/), create profile and copy your key.

![getapikey](https://i.imgur.com/28gAgkE.gif)

## How to use
It is really easy! Just drag and drop file into the app and voila!

![usage](https://i.imgur.com/iEpbruh.gif)

Alternatively you can add VirusTotal Uploader to file content menu and click on file and select "Scan with VirusTotal".

![usage](https://i.imgur.com/1IZu0Gs.gif)

## Contributing
If you have any idea how to make this app better, please create pull request. If you find any bug, please create issue.

## TODO

 - Make file splitter to upload files larger than 150M
 - Compress files before upload
 - ~~Make window frame dark in darkmode~~ ✓
 - Make code more readable for other people
 - Comment code
 - ~~Save settings to something more than just txt file~~ ✓

## License
This project is licensed under GPLv3. Please see [LICENSE file](https://github.com/SamuelTulach/VirusTotalUploader/blob/master/LICENSE).

