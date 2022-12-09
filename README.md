# The West Lake

The West Lake is a reverse shell executable generator for windows. While the executable is created with RUST, the generator itself is written in Python 3. The unique features of this reverse shell is :
-> It is Fully Undetectable (FUD) [0 detection on VirusTotal]
-> It can bypass Windows 11 Defender
-> It depends on relatively fewer libraries than most fancy FUDs out there.
-> It is minimalistic and simple to use

# The OPPS Server

The OPPS Server is a Controlling server to which the malicious executable connects back. It allows the attacker to gain shell access to the victim's machine and perform some actions. It allows the attacker to :
-> Upload files to the victim machine.
-> Download files from the victim machine.
-> Browse some website using the victim's browser
-> Check if the victim has access to the internet.
-> Check for WiFi credentials
-> Shell Access
