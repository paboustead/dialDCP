## Installation 

Installation instructions:
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;Install latest Node LTS distribution for your platform from https://nodejs.org/
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;npm install

[Optional] Create native binaries for Linux, Windows, OS X
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;npm i pkg -g
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;pkg .
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;This will create the following binaries: dcpdial-linux    dcpdial-macos    dcpdial-win.exe  



Usage: dialDCP [options] --ip <ip_address> --number <phone_number>

Options:<br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-V, --version                 output the version number <br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-i, --ip <ip_address>         DCP IP Address <br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-n, --number <phone_number>   Phone number to dial <br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-u, --user <user_name>        Phone username (default: "admin") <br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-p, --password <password>     Phone password (default: "1739") <br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-v, --verbose                 print detailed logs <br/>
&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;-h, --help                    display help for command <br/>


Example: bin/dialDCP -i 192.168.2.1 -n 5555555555
Example: ./dcpdial-linux -i 192.168.2.1 -n 5555555555
Example: ./dcpdial-macos -i 192.168.2.1 -n 5555555555
Example: ./dcpdial-win.exe -i 192.168.2.1 -n 5555555555

