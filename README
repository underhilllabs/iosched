How to Update the App code for your Convention
===============================================

1. Create a google spreadsheet with 3 worksheets, title them: sessions, speakers, sandbox.  
2. Pusblish the worksheet as an atom stream: 
	a. Share->Publish as a web page->Sheets to publish "all sheets".
	b. grab the atom URL.
3. edit src/com/google/android/app/iosched/service/SyncService.java
	change WORKSHEET_URL to be the atom URL from 2.b. up above.
4.a. add the following columns to sessions worksheet: sessiondate, sessiontime, room, product, track, sessiontype, sessiontitle, tags, sessionspeakers, speakers, sessionabstract, sessionrequirements, sessionlink, sessionhashtag, fulllink, youtubelink, pdflink, moderatorlink, waveid, wavelink
(sessionlink MUST be filled in and unique!)
4.b. add the following columns to the speakers worksheet: speakertitle, speakercompany, speakerabstract, speakerldap
4.c. add the following columns to the sandbox worksheet: companyname, companylocation, companydesc, companyurl, productdesc, companylogo, companypod, companytags
5. replace images in res/drawables, etc with your conventions logos.
6. 



About the Original App
=========================
Google I/O is a developer conference held each year with two days of deep technical content featuring over 90 sessions, more than 5,000 developers, and over 180 demonstrations from developers showcasing their technologies.

This project is the Android app for the conference, including these features and more:

Conference schedule with calendar-block overview.
Detailed session info that is full-text searchable.
Info about companies in the Developer Sandbox.
Star sessions and Sandbox companies.
Conference map and take notes on sessions.
