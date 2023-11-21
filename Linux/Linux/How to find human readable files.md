https://www.systranbox.com/how-to-find-only-human-readable-files-in-linux/

Current Directory 
- find . -readable -type f
Grep
- `grep -IRl –exclude-dir=”.*” .`
Specific Directory
- find /etc -type f -readable
-  `grep -r –exclude-dir=”.*” /etc .`

