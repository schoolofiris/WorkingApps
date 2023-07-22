This GUI application scans the tcp port of a target ip address or remote host, for a range of ports given as input.
The code demonstrates various python concepts and module 
- socket programming
- threading
- regex for input validation
- queue data structure
- Tkinter UI (customTkinter module)
- importing custom module for code reuse

core logic of the program lies in the portscan function. where the code tries to initiate a socket connection with the target IP and port 
if the connection is successful, the code will return TRUE
if connection fails, code will return ERROR. with TRY-EXCEPT block, the code returns FALSE value instead of throwing ERROR.
