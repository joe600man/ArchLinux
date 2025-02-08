copy a file vs move a file

```
cp /etc/i3status.conf ~/.config/i3status.conf
```
copies the file 'i3status.conf' from the /etc/ directory to the ~/.config/ directory, retaining the same file in the original directory. This is good for ensuring you have a backup of premade conf files. 

```mv``` will move the file from one place to another. Contrary to ```cp```, ```mv``` will take the whole thing with it to a new location.

```
mv ~/Desktop/Everything/File1.txt ~/Desktop/Else
```
