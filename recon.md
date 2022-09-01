## NMAP
baseline nmap stealth scan: `sudo  nmap -Pn -sS -T2 -vvv <ip-address>`   
 - `-Pn`: treat all hosts online
 - `-sS`: TCP SYN check, doesn't complete TCP handshake
 - `-T2`: Timing template of 2
 - `-vvv`: verbosity level 3

 for additional ports, `-p <range>` or `--top-ports <number>`
