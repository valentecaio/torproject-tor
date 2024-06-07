This repository is a personal fork of the Tor Project that I created when contributing to Tor with improvements to its IPv6 support.  
This happened in 2018 as a project for my master's degree in Computer Engineering, in France (Telecom Bretagne).  
Each active branch of the repo is a ticket of the Tor bug-tracker that I worked on.  
[You may find more information in this technical report.](https://drive.google.com/file/d/1kqV7co4ilmaGUUuAuVeeL4eNn7Wyqi1W)
  
  
  
  
  
  
--------------------------------------------------

Tor protects your privacy on the internet by hiding the connection
between your Internet address and the services you use. We believe Tor
is reasonably secure, but please ensure you read the instructions and
configure it properly.

To build Tor from source:
        ./configure && make && make install

To build Tor from a just-cloned git repository:
        sh autogen.sh && ./configure && make && make install

Home page:
        https://www.torproject.org/

Download new versions:
        https://www.torproject.org/download/download.html

Documentation, including links to installation and setup instructions:
        https://www.torproject.org/docs/documentation.html

Making applications work with Tor:
        https://wiki.torproject.org/projects/tor/wiki/doc/TorifyHOWTO

Frequently Asked Questions:
        https://www.torproject.org/docs/faq.html


To get started working on Tor development:
        See the doc/HACKING directory.

Release timeline:
         https://trac.torproject.org/projects/tor/wiki/org/teams/NetworkTeam/CoreTorReleases
