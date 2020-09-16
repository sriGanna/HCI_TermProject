---
layout: default
---

# Project Team 


Rayan      | Linnea        |  Sri
:-------------------------:|:-------------------------:|:-------------------------:
![Sri](assets/images/rayanIsran.png) |![Linnea](assets/images/linnea.jpg)  |  ![Rayan](assets/images/Sri.jpg)


# Proposal

## Refining Feedback Mechanisms for Virtual Presentations

Popular videoconferencing apps like Zoom make it difficult for listeners to unobtrusively respond to a lecturer or presenter. Zoom has attempted to allow users to signify indicators such as Raise Hand, Thumbs Up, and Thumbs Down, but the interface for doing so is hard to find and it is easy to miss the responses. Also, the responses do not decay, so unless the host clears all responses or all users undo their response after some time, the responses display even after becoming irrelevant.

We propose an interface that works alongside a videoconferencing app and allows listener feedback to be present, yet unobtrusive. Our goal is to allow a speaker to have background awareness of the feedback  without disrupting their flow of speech. Because we do not want to have to tweak an existing videoconferencing app, our intended interface would be a separate, transparent window that would overlay the videoconferencing app.

Some livestreaming apps such as Facebook Live display reactions floating across the screen. Our interface would take that idea and build upon it. When a listener gives input, the corresponding icon will float across the screen as well as increment a counter at the bottom of the screen. This small tweak to previous implementations would allow speakers to monitor when they would like to pause to address any questions or clarify any material. In addition, we would like to add a side panel that displays all input more verbosely, i.e. a queue of paired names and inputs that can be filtered by input type. 

On the listener's side, we think it is important for the feedback to feel the same as it would in an in-person classroom or meeting situation, e.g. physically raising a hand to indicate you want to ask a question instead of clicking a button. We would like to create a wearable device that would use an Arduino board  to turn physical gestures into their digital representation on our interface. Gesture recognition using Arduino has already been implemented, so we would just need to adapt it to suit our needs.[2] If the gesture recognition ends up being too finicky, it would be easy to simplify our idea by instead creating a button interface. The hardware components mentioned above are all relatively cheap to purchase, reducing the barriers of entry. With regards to input decay over time, instead of a boolean on/off system, we think the input would continue to stay valid as long as the listener is making the gesture (or pressing the button). In this way we are able to mimic what would happen in an in-person setting, e.g. a student raising their hand and then putting it back down when the question either is answered or becomes irrelevant.


> References:
[1] https://arlingtonentrepreneurs.org/5-great-ideas-to-use-facebook-live-to-market-your-business/ 
[2] https://create.arduino.cc/projecthub/mellis/gesture-recognition-using-accelerometer-and-esp-71faa1



# Observations 


# Personas





