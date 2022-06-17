# What is Footprinting ?
Footprinting is the first step in Hacking which is just gather maximum information about a computer system or a network and about any device connected to that network

## Types of footprinting 
one is Passive and Second is Active
*Passive* Footprinting invloves gathering information about the target without direct interaction .
PASSIVE techniques
1. Finding information through search engines 
2. Finding top level domains ans Sub-Domains of a target through web services 
3. Perfotming search in Socail media platforms 
4. Gathering financial information
5. Gathering infrastuctures through job sites
6. Collecting infomation through deep and dark web footpriting
7. Determining the operating System 
8. Performing competetive intelligence 
9. Monitoring the target using alert services
10. Gathering information using groups,formns,blogs,and NNTP Usenet newsgroups
11. Monitoring website traffic of the target
12. Tracking the online reputation of the target
*Active*Footprinting gathering information about the target with direct interaction.
Active Footprinting techinques:
1. Quering published name servers of the target 
2. Searching for digital files
3. Extracting Website links and gathering wordlists from the target website 
4. Exacting metadata of pusblished documents and files 
5. Gathering Website info using web spiders and mirroring tools 
6. Gathering information through email tracking 
7. Haravesting email lists 
8. Performing Whois lookup
9. EXtracting DNS information
10. Performing traceroute 
11. Social engineering

## Infomation obatained by footprinting
**Organization Information**:
1. Employee details 
2. Address and mobile /telephone number
3. Partners of the organization 
4. Web links
5. Web technoogies
6. News articals, press realeas and related documents
7. Legal documents realted to the organization
8. Patents and trademarks realated to the organization
**Network Information**:
1. Domain and sub-Domains
2. Network blocks
3. Network topologies, trusted routers, and firewalls
4. IP address of the reachable systems
5. Whois records
6. DNS records and realated information
**System information**:
1. Web servers OS
2. Location of web servers
3. Publicaly available email addresses
4. Usernames,passwords and so on.

# Footprinting techniques ?
1. Through search engines
2. Through web servers
3. Through Social media
4. Website Footprinting
5. Email footprinting
6. Whois
7. DNS footprining
8. Network footprinting
9. Social Enigineering

## Footptinting through search enignes
A search engine can reveal a very helpfull data
**Techniques -1**
Google Dorking also known as advanced google search operators and the query 
EX- 
`www.noob.com file:pdf`
here the file is known as *search_term* and use to modify search this will show only pdf file type

## The Google hacking database [EXploit-db]
This is use to find CVE exploits
Google Hacking DB (GHDB)
Authoritative source for querying Google. The Exploit DB is a Common Vulnerabilities & Exploits (CVE) compliant archive. You can also footprint, VoIP and VPN here
*SHODAN Search Engine*
is the computer search engine that searches the Internet for connected devices (routers, servers, and IoT.).
You can use to discover which devices are connected to the Internet, where they are located and who is using them. 
*Censys*a search engine that enables researchers to ask questions about the hosts and networks that compose the Internet.
Censys collects data on hosts and websites through daily ZMap and ZGrab scans of the IPv4 address space, in turn maintaining a database

## Footprinting Top-Level Domains (TLDs) & Sub-domains
Search for company's external url :Google, Bing,Sub-domains provide insight into internal departments
Sub-domains can be found by trial and error or by using netcraft or Sublist3r (python script that enumerates sub-domains across multiple sources at once.


# Google Dorking:
The Adavanced google search_term
**Operators:**
1. *site :*  this operator restricts search results to specific site or domain EX- `games site:www.hacker.com`
2. *allinurl :*  This operators restricts result only the pages conataining all the query terms specified in URL EX- `allinurl:google carrier`
3. *inurl :* This operator restricts the result to only the pages containing the specified word in the url EX- `inurl:copy site:www.google.com` 
4. *allintitle :*This operator resticts result only the pages containing all the query terms specified in the title EX- `allintile: detect malware` 
5. *intitle :* This operator resticts result to only the pages containing the specified term in the title EX- `malware detection inititle: help `
6. *inanchor :* This operator resticts result to only pages containing the specified term in the specified in the anchor text or links on the page  EX-`Antivirus inanchor: Norton`
7. *allinanchor :* This operator resticts result to only pages containg the query terms in the anchor text on links to the pages EX- `allinanchor : best cloud service provider`
8. *cache :* This operator displays Google's cached version of a web page, instead of the current version of the web page EX- `cache: www.eff.org`
9. *link :* This operator searches  websites or pages that contain links to the specific website or page EX-`link:www.google.com` 
10. *related :* This operator dsiplays website that are similar or related to the URL specified. EX- `related : www.microsoft.com` 
11. *info :* This operator finds information about the specified web page . EX- `info : gothotel.com`
12. *location :* This operators find information for a specific location EX- `location : 4 seasons restraunt` 
13. *filetype :* This operators allows you to search specific file type. EX- `file: pdf or jasmine:jpg`

# Cynsis
# SHODAN
# Netcraft


## Footprinting: Geo-locating Tools 
-Google Earth
-Wikimapia
-Bing Maps
-Yahoo Maps
-National Geographic maps
## Footprinting: People Search Tools
pipl
Intelius
BeenVerified
Spokeo
AnyWho
US Search
411
Veromi
PrivateEye
Public Background Checks
Zaba Search
WebMii
InSpy
TechSpy
EmpSpy
## Footprinting: Financial Services
Yahoo! Finance,
TheStreet,
MarketWatch
Google finance
## Footprinting: Job Sites 
-Glassdoor,
-LinkeIn,
-Monster,
-Indeed
## Footprinting: Alerts
-Google Alerts,
-Twitter Alerts,
-Giga Alert
-TalkWalker Alerts
## Footprinting: Groups, Forums, Blogs
-Fully Qualified Domain Names (FQDNs),
-IPs,
-usernames
-Google Groups,
-Yahoo Groups
-Register with fake profiles and social engineer the organizations employees

## Footprinting: Websites
1. Monitoring and analyzing target website
2. May provide SW use, OS use, sub-dirs. & file paths, contact info
3. Tools - BurpSuite, ZaProxy, Paros Proxy, Firebug and website informer
These tools allow attacker to view headers that provide connection status and type, accept-ranges and last-modified info, x-powered-by information, web server in use and its version

1. Examining HTML souce provides and coments
2. Contact details of web developer
3. File system structure and script type
4. Examining cookies may provide
5. Software in use and its behavior
6. Scripting platforms used

## Footprinting Websites: Web Spiders
1. Extractor
2. SpiderFoot
3. Visual-seo,
4. Wildshark
5. Beam us up
6. Scrapy
7. Streaming Frog
8. Xenu
9. Web Data
10. Sublist3r 
## Competitive Intelligence 
How it began
1. EDGAR Database

How it developed
1. hoovers
2. BusinessWire

Company plans?
1. MarketWatch
2. Wall Street Transcript,

-FACTIVA- journal reviews
-LexisNexis - Legal info

## Competitive Intelligence Resources 
1. Business origins/development: EDGAR database,
2. Hoovers
3. LexisNexis,
4. Business Wire
5. Business Plans/Financials:
6. SEC Info
7. Experian
8. Market Watch
9. Wall Street Monitor
10. Euromonitor

## Passive Footprinting Sites 
Copying a website directly to your system to test offline 

1. HTTrack
2. Black Widow
3. WebRipper
4. Pavuk
5. Teleport Pro
6. Gnu Wget
7. Backstreet Browser

## Extracting Metadata of Public Documents
1. Metagoofil -extracts metadata of public documents (pdf, doc, xls, ppt, docx, pptx, and xlsx) belonging to a target company.
2. ExtractMetadata
3. FOCA
4. Meta Tag Analyzer
5. BuzzStream
6. Analyse Metadata
7. Exiftool
8. Web Data Extractor

## Monitoring Web Pages for Updates and Changes

1. WebSite- Watcher helps to track websites for updates and automatic changes. When an update or change occurs, WebSite-Watcher automatically detects and saves the last two versions onto your disk
2. VisualPing
3. Follow That Page
4. WatchThatPage
5. OnWebChange
6. InfoMinder
7. UpdateScanner
8. Verisionista

## Email Footprinting Tools
1. emailtrackerpro - analyzes email headers and reveals information such as sender's geographical location, IP address and so on
2. mailtracking.com
3. GetNotify
4. ContactMonkey
5. Yesware
6. Read Notify
7. WhoReadMe
8. MSGTAG
9. Trace Email
10. Zendio

## Footprinting: Tracking online reputation of the target
1. Trachkur - provides social media monitoring
2. Brand24
3. Social Mention
4. ReviewTrackers
5. Rankur


# whois ?

 ## Finding IP Geolocation Information.
1. GeoIP Lookup Tool
2. GeoIP2

# DNS 
*Domain Name System:*
1. Ip gets transfered into a name
2. Each domain = namespace

53UDP = name lookup
53TCP = zone transfer

*Zone Transfer* =The act of copying a primary name server's zone file 

*DNS SRV Record*= Defines hostname/port of servers
*DNS SOA Record*:
1. Id's primary name server for the zone
2. Indicates authority for domain

*DNS PTR Record* = maps IP address to hostname
*DNS NS record*
Name Server
1. Defines the name servers within your namespace
2. Points to host's name server
*DNS MX record*
Mail Exchange
3. ID's your email servers within your domain
4. Points to domain's mail server
*DNS CNAME record*
Canonical Name
5. Provides for domain name aliases with your zone
6. allows aliases to a host
*DNS A record*
Address
1. Points to a host's IP address
*DNS RP record*
Responsible Person
*DNS HINFO*
Host information record
1. includes CPU type and OS
*DNS TXT record*
Unstructured text records
# Footprinting: DNS Interrogation tools
1. DIg
2. myDNSTools
3. Domain Dossier
4. DNS Data
5. ViewDNSWatch
6. NsLookup
# Foot Printing: Locate Network Range
Find range of ipaddress using ARIN whois database search tool

Can find range of IPs and subnet mask used by target org for the RIR Regional Internet Registry
DNSSEC
Domain Name System Security Extensions.
1. A suite of specifications used to protect the integrity of DNS records and prevent DNS poisoning attacks.


# Footprinting: Traceroute
1. Path analyzer pro - delivers network route tracing with performance tests, DNS, Whois, and network resolution to investigate network issues. It shows the route from source to destination graphically.
2. VisualRoute
3. Geo Spider
4. Trout, etc.

# Linux way of tracing packets 
traceroute

1. -4, -6: force ipv4/ipv6 tracerouting
2. -I: ICMP ECHO for probes
3. -T: TCP SYN for probes
4. -F: do not fragment packets
5. -m: max hops
6. -P: raw packet with set protocol
7. -n: prevents IP mapping to hostnames

# Windows way of tracing packets 
Tracert
1. -d -Do not resolve addresses to hostnames.
2. -h maximum_hops -Maximum number of hops to search for target.
3. -j host-list -Loose source route along host-list (IPv4-only).
4. -w timeout -Wait timeout milliseconds for each reply.
5. -R -Trace round-trip path (IPv6-only).
6. -S srcaddr -Source address to use (IPv6-only).
7. -4 -Force using IPv4.
8. -6 -Force using IPv6.

# Footprinting Tools: 
Maltego -shows relationships & real world links

Recon-ng -
FOCA & Recon-Dog

# Footprinting Tools: OSRFramework 
provide a collection of scripts that can enumerate users, domains, and more across over 200 separate service
-username checking, DNS lookups, deep web search and more
-usufy.py,
-mailfy.py,
-searchfy.py,
-domainfy.py,
-phonefy.py


# Footprinting Pen Testing
1. Get proper authorization
2.Define the Scope
3. Perform footprinting through search engines (google, yahoo, bing, ask)

4. Perform footprinting through web services (Netcrat, Pipl, Google Finance, Google Alerts)

5. Perform footprinting through social media (facebook, LinkedIn)

6. Perform website footprinting (Burp Suite, Web Data Extractor, HTTrack, Website Copier)

7. Perform email footprinting (emailTrackerPro, Yesware)

8. Gather Competitive Intel (Hoovers, LexisNexis, Business Wire)

9. Perform Whois footprinting(SmartWhois, Batch IP converter)

10. DNS footprinting (DNSstuff, DIG, MyDNSTools)

11. Network Footprinting (Path Analyzer Pro, VisualRoute)

12. Perform Social Engineering (evesdropping, shoulder surfing, dumpster diving)

13. Document all findings
