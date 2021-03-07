# NPS
NOCH's Port Scanner (NPS), a basic port enumeration CLI tool written in Python3.

# Prerequisites
* This script will work on windows, but uses UNIX based escape codes for colour outputs.
* Requires progressbar2 module
* Requires colorama module

# Installation
Get the script on your local machine by either:

1) Clone the respository:
(Recommended: change git core.autocrlf to input!)
<pre>git config --global core.autocrlf input</pre>
<pre>git clone https://github.com/nochhacks/NPS</pre>

2) Download the ZIP file directly from the "Code" drop down on the page, and unzip it.


<b>(Linux Only!)</b>

Give the script execute permissions so you can run it from the console.
<pre>cd /path/to/NPS</pre>
<pre>chmod +x NPS</pre>

If you want to be able to run the NPS command from anywhere in the terminal, you need to add the file location to the PATH variable. Add this line to the bottom of your .bashrc file:
<pre>export PATH=/home/path-to-b64-script:$PATH</pre>

<b>(Windows Only!)</b>
You should have Python added to PATH. 
See how to do this <a href="https://datatofish.com/add-python-to-windows-path/">here</a>.

You can execute the script from the DOS terminal; just go to the directory the "NPS" file is held in:
<pre>python b64 [option] "{string}" </pre>

# Usage

<pre>
USAGE: NPS -p- {host}

positional arguments:
  host                  Host IP to scan

optional arguments:
  -h, --help            show this help message and exit
  -p PORT, --port PORT  Port(s) to scan [Range: 1-65535, List: 1,2,3, Single: 80] (-p- For entire port range)
</pre>

