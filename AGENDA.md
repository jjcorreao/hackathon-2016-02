Working Document for BES/ASCR Network Performance Hackathon 
LBNL, Feb 23-26 2016
Wang Hall / CRT Building 59 Room 3034


Overview
Venue
Attendees
Draft Agenda
Work Plan:
Proposed Outcome Sketch:


Overview
A group of BES facilities directors has recently convened hackathons involving BES/ASCR staff regarding BES user facility data analysis. This document is the working area for the second hackathon on the topic of network performance. 

Given the relatively small cross section of interest on this topic currently, we have chosen to convene a small group of networking, data transfer node, and IT facility staff around the topic of network performance. The charge from the facility directors was for concrete outcomes, which we have chosen to address by building a simply map of network performance in and between BES facilities. 
Venue
For attendees coming to LBNL we will meet at LBNL at the new location of NERSC and ESnet, CRT/Wang Hall Room 3116. For attendees attending remotely please direct your browser here: 

 https://zoom.us/j/769389349

Day 1: PerfSonar installfest, Globus, DTNs, and DMZs

Day 2: Dashboard design and development.

Day 3: Further development and/or data transfer tuning based on above.
Attendees
Please update or comment on attendance (x = @LBNL, r = remote) or area of contribution. 

Name
Feb 23
Feb 24
Feb 25
Feb 26 
Area of contribution / interest 
Dave Wallis 
x
x
x
x
APS DTN data 
Roger Sersted
x
x
x
x


Raj Kettimuthu
x
x
x


Globus data 
David Skinner
x
x
x
x
Facilitator, Co-organizer
Joaquin Correa
AM
x
x
x
UI, NERSC DTN data
Michael Smitasin and/or Vince Stoffer
x
x
x
x
LBNLnet networking data
Jason Zurawski
x
x
x
r
ESnet, Co-organizer 
Antonio Ceseracciu 
x






SLAC networking data, Co-organizer
Dantong Yu 








NSLS-II
Simon Patton 








ALS workflow data 
Robert Petkus










Alexei Klimentov










Shigeki Misawa










Craig Tull








ALS workflow data
Wilko Kroeger
x






LCLS DTN data 
Igor Gaponenko


x
x


LCLS workflow data
Doga Gursoy








UI
Peter Murphy


x




ESnet, UI
Sowmya Balasubramanian
x






ESnet, perfSONAR
Gunther Weber


?
x
?
LBL, visualization, user interface


Draft Agenda
Tue Feb 23       9:00 AM -  10:00 AM        Welcome and building tours 
        10:00        - 10:30         Background on charge from BES directors 
        10:30        - 11:30         Round table intros from each facility (1-2 slides) 
        11:30        - 12:00        Target setting for Hackathon#2 outcomes 
        12:00 PM  -  1:00 PM        Lunch 
          1:00        -   3:00        PerfSonar work (Training materials: http://www.perfsonar.net/about/training-materials/ ), ELK (Elasticsearch, Logstache, Kabana)
          3:00        -   3:30        Break 
          3:30        -   5:00        DTN census and survey 

Wed  Feb 24     9:00 AM -  10:00 AM        Software methods and coordination  
        10:00       -   12:00          15 Min Tech Shares: NERSC (Cori WAN), ESnet Portal and APIs
        12:00       -     1:00         Lunch in Auditorium (*)
          1:00       -     5:00        Data organization tasks  

Thu  Feb 25      9:00 AM -  10:00 AM        Updates from work teams  (software) 
        10:00       -   12:00          Draft UI tasks 
        12:00       -     1:00         Lunch
          1:00       -     5:00        Map UI tasks  

Fri  Feb 26        9:00 AM -  10:00 AM        Updates from work teams  (opportunities) 
        10:00       -  12:00          Demo presentation   
        12:00       -    1:00         Lunch
          1:00       -    5:00        Deliverable wrap-up   
 
(*) Title:  From table-top laser plasma accelerator to future free electron laser
Speaker:  Jeroen van Tilborg, LBNL
Date:  Wednesday, February 24, 2016
Time: 12:00-1:00 PM (Please feel free to bring your lunch)
Location:  Bldg. 50 Auditorium 

Work Plan:
What are the data sources we will draw on? 
What details will the map communicate?
What technologies will we use for display?
Work items that advance these goals and/or what we come up with. 


S1
Initiate inter-facility collaborations in network performance informed by recent BES and ASCR requirements reviews and reports.
S2
Deliver a BES-wide “data map” dashboard (static or preferably dynamic web page) that gives facility directors a view of data flowing in and out of BES endpoints.
S3
Deliver network performance improvements or plans toward improvements.
S4
Demonstration of benchmarking practices for end-to-end data workflows.
S5
Formulate organizational suggestions for the next hack-a-thon. 
L1 
A shared high performance data environment across BES facilities, e.g. DTNs and DMZs, leveraging common design and best practices in operation.
L2
Acceleration of BES workflows through advanced networking. 



Proposed Outcome Sketch:

From: LBNL and SLAC
To: BES Facilities Directors
Date: End of February 2016 

We recently held our second BES / ASCR hackathon Feb 23-26 at LBNL. The topic was “network performance” which drew interested attendees from APS, LCLS, ALS, NSLS-II, ESnet, and NERSC facility staff. Recognizing the increasing role of networks in marshalling BES data analysis workflows, we chose to answer your charge with a simple map of the BES user-facility ecosystem. We hope it is useful in furthering a complex-wide understanding of emerging data analysis methodologies. It may also be useful at the upcoming RDA meeting in Tokyo where an international discussion of neutron and lightsource data analysis is planned. 

It is not production software. One of the advantages BES enjoys in developing software frameworks in the current era should be choosing software development best practices that will lead to world-class software capabilities. Hackathons are just a start, and fall under the category of “what you can do for little to no cost.” The staff attending voted X to Y that it was useful event in furthering their understanding of network performance. 

URL to map

We hope it is useful. We feel it provides a basic map of the major areas of data production and network flows at these user facilities. A detailed set of hackathon notes are attached. In addition to the deliverable above the following executive summary describes the hackathon outcomes. 

Sincerely, 

Undersigned 



Appendix / Notes

BES charge 

From: Hill, John <hill@bnl.gov>
Sent: Wednesday, September 09, 2015 6:30 PM
To: Proffen, Thomas E.
Cc: 'Roger Falcone'; Streiffer, Stephen; Dunne, Michael; Gaffney Kelly
Subject: Follow up to your report
 
Dear BES Facilities Computing Working Group,
 
We would like to thank you very much for your considered and detailed response to our recent charge. We found your report both  thought provoking and extremely useful, and there is much to think about and digest. While that happens, however we would to take up two of your suggestions immediately.
 
First, the idea of hack-a-thons on problems of mutual interest strikes us as an extremely productive way to push inter-facility collaboration forward. We would therefore like to ask you to organize three such meetings. Expecting each to be roughly a week or so in length we suggest the following locations and themes:
1.      BNL: Live pipelining/livestreaming data analysis. To be held this fall
2.      SLAC/LBNL: Multi-modal data analysis. To be held early in CY16
3.      ANL: Network performance – including into and out of ESnet. To be held in spring 2016
 
We ask you, for each of these, to
1)      Refine the theme in ways that make sense and define deliverables for the hack-a-thon
2)      Develop longer term goals for each area with a roadmap and timeline
3)      Determine a point of contact from the host institution to direct the efforts.
 
Please communicate these to us for the first event, together with dates for that event, by September 25th.
 
Our expectation is that these events would involve the coders themselves (that is not necessarily the BESFCWG directly) and mark a kick-off of a more extended effort in each case once the coders return to their home institutions. Code should be written following agreed upon standards and useful to all facilities involved. Support for travel expenses will be provided by the home institutions of the coders (not the host institution of the hack-a-thon).
 
After the first one is held, we would appreciate feedback on the format and approach to incorporate into the following events.
 
In addition to the hack-a-thons we would like to follow up on your suggestion of a white paper entitled “Combined BES Data and Analysis Roadmap.” We think that this is an excellent idea and written jointly by yourselves would be a very useful document in both laying out the path forward in these areas and in ensuring the facilities work together in a mutually beneficial way. In this regard, we are aware that there is a joint ASCR-BES requirements workshop in early November. We ask that those of you at that workshop reflect the thinking behind your report to our first charge at that workshop, and similarly fold the discussions at that workshop into the roadmap white paper. Bringing ASCR into our thinking and vice versa could be a powerful way to generate the new funding required to support this enterprise long term. We ask that the roadmap white paper be delivered to us by January 1st 2016.
 
Thank you again for your efforts, we recognize that this is an extremely important topic for the future success of our facilities and now is a critical time to act. We very much appreciate your work in this area.
 
John
Mike
Roger
Kelly
Stephen




example data from ALS

Fri Feb 5 21:39:37 PST 2016: submitPostGalJob.sh:69:1084664-62990:PERF:SUBMIT_POST_GAL-render-norm:START_DATE=1454737177
Fri Feb 5 21:40:43 PST 2016: submitH5PackJob.sh:84:1084664-62990:PERF:SUBMIT_H5-sino:START_DATE=1454737242
Fri Feb 5 21:41:09 PST 2016: submitH5PackJob.sh:84:1084664-62990:PERF:SUBMIT_H5-gridrec:START_DATE=1454737268
Fri Feb 5 21:41:29 PST 2016: submitRingRemJobs.sh:108:1084664-62990:PERF:SUBMIT_RINGREM_gridrec:START_DATE=1454737287
Fri Feb 5 21:49:52 PST 2016: submitRingRemJobs.sh:108:1084664-62990:PERF:SUBMIT_RINGREM_imgrec:START_DATE=1454737790
Fri Feb 5 21:56:15 PST 2016: submitSuperGalJob.sh:91:1084664-62990:PERF:SUBMIT_GAL-gal-sino:START_DATE=1454738163
Fri Feb 5 21:56:32 PST 2016: submitSuperGalJob.sh:91:1084664-62990:PERF:SUBMIT_GAL-jpgs-sino:START_DATE=1454738190
Fri Feb 5 21:59:28 PST 2016: submitSuperGalJob.sh:91:1084664-62990:PERF:SUBMIT_GAL-render-sino:START_DATE=1454738367
Fri Feb 5 22:03:43 PST 2016: submitSuperGalJob.sh:91:1084664-62990:PERF:SUBMIT_GAL-gal-gridrec:START_DATE=1454738609
Fri Feb 5 22:04:58 PST 2016: submitSuperGalJob.sh:91:1084664-62990:PERF:SUBMIT_GAL-jpgs-gridrec:START_DATE=1454738696
Fri Feb 5 22:13:48 PST 2016: submitSuperGalJob.sh:91:1084664-62990:PERF:SUBMIT_GAL-render-gridrec:START_DATE=1454739226
Fri Feb 5 22:25:32 PST 2016: submitPostGalJob.sh:69:1084664-62990:PERF:SUBMIT_POST_GAL-jpgs-sino:START_DATE=1454739932
Fri Feb 5 22:25:51 PST 2016: submitPostGalJob.sh:69:1084664-62990:PERF:SUBMIT_POST_GAL-render-sino:START_DATE=1454739950
Fri Feb 5 22:26:10 PST 2016: submitPostGalJob.sh:69:1084664-62990:PERF:SUBMIT_POST_GAL-jpgs-gridrec:START_DATE=1454739970
Fri Feb 5 22:26:29 PST 2016: submitPostGalJob.sh:69:1084664-62990:PERF:SUBMIT_POST_GAL-render-gridrec:START_DATE=1454739988
Fri Feb 5 22:26:49 PST 2016: submitH5PackJob.sh:84:1084664-62990:PERF:SUBMIT_H5-rc-gridrec:START_DATE=1454740008
Fri Feb 5 22:34:50 PST 2016: submitSuperGalJob.sh:91:1084664-62990:PERF:SUBMIT_GAL-gal-rc-gridrec:START_DATE=1454740477
Fri Feb 5 22:35:09 PST 2016: submitSuperGalJob.sh:91:1084664-62990:PERF:SUBMIT_GAL-jpgs-rc-gridrec:START_DATE=1454740507
Fri Feb 5 22:38:49 PST 2016: submitSuperGalJob.sh:91:1084664-62990:PERF:SUBMIT_GAL-render-rc-gridrec:START_DATE=1454740728
Fri Feb 5 22:43:10 PST 2016: submitPostGalJob.sh:69:1084664-62990:PERF:SUBMIT_POST_GAL-jpgs-rc-gridrec:START_DATE=1454740989
Fri Feb 5 22:43:30 PST 2016: submitPostGalJob.sh:69:1084664-62990:PERF:SUBMIT_POST_GAL-render-rc-gridrec:START_DATE=1454741009
Sat Feb 6 10:36:14 PST 2016: rabbitSubmitBL832Jobs.sh:1143:1086857-64636:PERF:SUBMIT:QSTART_DATE=1454783748
Sat Feb 6 10:36:14 PST 2016: rabbitSubmitBL832Jobs.sh:1144:1086857-64636:PERF:SUBMIT:WSTART_DATE=1454783773
Sat Feb 6 10:36:28 PST 2016: submitFastTomoPyJob.sh:65:1086857-64636: PERF:SUBMIT_FAST_TOMOPY:START_DATE=1454783787
Sat Feb 6 10:36:40 PST 2016: submitSuperGalJob.sh:91:1086857-64636:PERF:SUBMIT_GAL-gal-raw:START_DATE=1454783798
Sat Feb 6 10:36:55 PST 2016: submitSuperGalJob.sh:91:1086857-64636:PERF:SUBMIT_GAL-jpgs-raw:START_DATE=1454783814
Sat Feb 6 10:40:17 PST 2016: submitSuperGalJob.sh:91:1086857-64636:PERF:SUBMIT_GAL-render-raw:START_DATE=1454784010
Sat Feb 6 10:43:33 PST 2016: submitNormJobs.sh:32:1086857-64636: PERF:SUBMIT_NORM:START_DATE=1454784213
Sat Feb 6 10:46:40 PST 2016: submitRotJob.sh:65:1086857-64636:PERF:SUBMIT_ROT:START_DATE=1454784400
Sat Feb 6 10:47:30 PST 2016: submitSuperGalJob.sh:91:1086857-64636:PERF:SUBMIT_GAL-gal-fast-tomopy:START_DATE=1454784449
Sat Feb 6 10:47:45 PST 2016: submitSuperGalJob.sh:91:1086857-64636:PERF:SUBMIT_GAL-jpgs-fast-tomopy:START_DATE=1454784465
Sat Feb 6 10:48:19 PST 2016: submitSuperGalJob.sh:91:1086857-64636:PERF:SUBMIT_GAL-render-fast-tomopy:START_DATE=1454784498
Sat Feb 6 10:48:52 PST 2016: submitPostGalJob.sh:69:1086857-64636:PERF:SUBMIT_POST_GAL-jpgs-raw:START_DATE=1454784532
Sat Feb 6 10:49:07 PST 2016: submitPostGalJob.sh:69:1086857-64636:PERF:SUBMIT_POST_GAL-render-raw:START_DATE=1454784547
Sat Feb 6 10:49:25 PST 2016: submitSinoJobs.sh:104:1086857-64636:PERF:SUBMIT_SINO:START_DATE=1454784562



http://speedpage.psc.edu/

Example of perfSONAR Data between Leadership Class Facilities: http://lcf-dashboard.es.net 

Possible perfSONAR Resources:
JSON Mesh File: http://ps-west.es.net/bes-mesh.json 
ESnet perfSONAR:
anl-pt1.es.net
anl-owamp.es.net
bnl-pt1.es.net
bnl-owamp.es.net        
slac-pt1.es.net
slac-owamp.es.net            
ornl-pt1.es.net
ornl-owamp.es.net    
lbl-pt1.es.net
lbl-owamp.es.net
ESnet DTNs:        
lbl-diskpt1.es.net
bnl-diskpt1.es.net
anl-diskpt1.es.net
cern-diskpt1.es.net
ANL
anlborder-ps.it.anl.gov
prfsnr-prism.aps.anl.gov
192.5.180.130
typhoon.pub.alcf.anl.gov
BNL:
lhcmon.bnl.gov
lhcperfmon.bnl.gov
SLAC
psnr-lat01.slac.stanford.edu
psnr-farm04.slac.stanford.edu
ORNL:
perfsonar.ornl.gov
perfsonar1.ccs.ornl.gov
LBL (Michael Smitasin <mnsmitasin@lbl.gov>):
ps-sr1-als-bwctl.lbl.gov
ps-sr1-als-owamp.lbl.gov
perfsonar.nersc.gov

