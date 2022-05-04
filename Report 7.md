**1.0 Scope**
        	Our team has a good knowledge of what our clients want based upon our initial meeting. We can see how this type of video can entice viewers thinking about making the trip to say ‘this looks like a great place, let’s plan a trip’. We have outlined a few requirements that we think will lead to a completed product on time.
 
**1.1 Introduction:**
	The project ‘VR Video Tours of the Quartermaster Depot’ was assigned to Team #2 of the APCV498 Spring 2022 class at the University of Arizona. The members of Team #2 consist of John Carroll, Cesar Flores, Matt Trimmings, and Shane Vickers. The VR Video Tours project will be delivered to Tammy Snook and Brett Frame who represent the Colorado River State Historic Park  located in Yuma, AZ. 
	This outline will show how the different parts of the project were broken down into smaller sections that allowed Team #2 to divide the work and ensure project deadlines were met. With the use of different strategies such as a requirement identification and breakdown, using visual representation of tasks thanks to UML diagrams, and with project management tools such as GitHub, Team #2 was effectively able to manage and set realistic milestones for the project.
	The project itself is an attempt to entice new visitors to take a trip to the Quartermaster Depot by giving them a small tour in a virtual reality environment. Video walkthroughs have been around for ages, but utilizing 21st century technology to enhance the experience has a high potential of attracting new customers. The balance of this project will be between showing enough VR video to entice a visit but not so much video that it removes the need to visit the park. Strategy wise, the project is fairly straightforward. Cesar Flores, being local to Yuma, AZ where the park is located, will film on location and the team will use Matterport VR camera software to manage the raw video. The VR video, once edited, will then be uploaded to a site managed by AZ park personnel. 

**1.2 System Features and Requirements**
Requirements evolved quite a bit over the first few weeks of the course. The course document from NASA that discussed wording and structure was immensely beneficial in setting up a proper requirement (NASA, 2016).
Functional Requirements:
-The video shall show the inside & outside of buildings as well as the routes to and from.
-The video must not show too much so that visitors will still desire to visit the park.
-Ease of use and a UI that makes sense
Non-Functional Requirements:
-The video should not move too slow/fast.
-The video shall be in a full 360/
virtual reality environment.
Global Requirements:
-The user will have the license to use the camera
-Must procure license (or give info to the park) so that the park can use the finished video
-Must have access to the website or to contact with the website owner
-Tie into the current website as seamlessly as possible
Product/Project Constraints:
-Learning curve with using the camera / software
-Understanding how much video to record to accomplish a tour
-Identifying what needs to be recorded versus what would be nice to have

**2.0 Requirements Breakdown Structure (RBS)**

![Figure1](https://user-images.githubusercontent.com/99999681/166712873-add6a46c-8f54-4938-af74-531b1aa7b965.png)
Figure 1. Requirements Breakdown Structure.

**3.0 GitHub Repository**

https://github.com/mjtrimmings/APCV498_SP22_Team-2

The GitHub repository has an initial Read Me section that outlines the course objectives followed by our reports documenting the progress throughout the semester thus far. After submitting reports to the Professor, I have translated them into a format that allows GitHub to display them properly. Reports are updated as needed as well.

![Figure2](https://user-images.githubusercontent.com/99999681/166712904-398ba738-4ac4-417a-ab5f-0b07c27a650c.png)
Figure 2. Screenshot of our GitHub main page depicting the available Read Me section as well as the individual reports.  

**4.0 Software and Design Documents**
 
 ![Figure3](https://user-images.githubusercontent.com/99999681/166712974-1f62e4ea-83fe-4e0e-a6d0-517a510ca507.png)
 Figure 3. UML Sequence diagram showing the steps when a user wants to view the Virtual Reality video that will be hosted on the Stakeholders Website. Behind the scenes the browser will process the request from the user and reach out to the Matterport Cloud Server where the video is stored. 
 
 ![Figure4](https://user-images.githubusercontent.com/99999681/166712990-136ea972-2ab1-4679-84ce-e8f324162800.png)
 Figure 4. UML Use-Case Diagram that shows the simple layout and affected users of the video within the scope of the website. There will be an embedded video player in the website and the user may also have the option to login to the website, additionally it may end up being required to login in order to see the video, though that is beyond the scope of this project.
 
 ![Figure5](https://user-images.githubusercontent.com/99999681/166713000-becd00fd-7c58-4fcd-93aa-b0e5bda9d578.png)
 Figure 5. UML Use Case diagram showing how a user would expect to navigate through the web UI’s current toolbars in order to reach the VR video portion of the website. From the Yuma Park’s home landing page, a user should be able to easily find the VR video offerings with the Quartermaster being the first but easily expandable to other locations if needed.

![Figure6](https://user-images.githubusercontent.com/99999681/166713012-c4a3ba64-e40d-4fac-add7-b964c6c3bc65.png)
 Figure 6. UML Sequencing diagram that gives a framework for how and where the VR video will be captured, where the video will be saved and edited, and where the video will be uploaded to. The process between the video being edited and uploaded will loop based on the results of the video being tested for content and quality. 

**5.0 Final Budget**
	Fortunately for this project, the University of Arizona already had a 3D camera and the necessary licensing for the camera software, so no additional expense was incurred for the bulk of this project. If anything, Cesar’s gas used to travel to and from the location would be the only current and remaining expenses for this project.
 
**6.0 Lessons Learned**
One of the aspects that went well about this project, and something that is vital to team projects in general, was our communication throughout the development process. The use of Microsoft Teams, GitHub, and Google Drive has allowed each member of the team to contribute on their own time and for everything to be in one convenient and easy to access place as well as keeping everyone aware of any updates that were taking place. Some aspects about this project that were difficult was that the bulk of this project was location dependent. A large part of the success and failure of this project relied on a single member of the team who happened to be local to the location where the 3D video footage had to be captured. Additionally, both class meeting times and stakeholder meetings were held during working hours. Even with the class meetings being recorded, it was difficult to feel included in the overall project process. With stakeholder meetings happening during working hours, some members of the team were unable to join or be fully committed to the meeting as they were also working during those hours.

	
**7.0 References** 

NASA. (2016). APCV 498: NASA Systems Engineering Handbook. [Course content]. https://d2l.arizona.edu/d2l/le/content/1118540/viewContent/11861000/View 


![image](https://user-images.githubusercontent.com/99999681/166710131-95a4c38b-25d2-4d64-92a5-e0cbd019664d.png)
