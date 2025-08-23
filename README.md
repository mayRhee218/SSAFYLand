## 🗺️ SsafyLand

A metaverse implementation of event venues for SSAFY members such as Ssafy Meet Up and SsafyDay.

## 👨‍👦‍👦 Team Members

- Kim Daye  
- Kim Seongwoo  
- Lim Hyeonmo  
- Rhee Myeongseong  
- Lee Sanghyun  
- Choi Daeho  

<br/>

## 📄 Project Overview

### **Duration** : 2022.04.11 ~ 2022.05.20

### Purpose of Planning

**SSAFY Meetup** is an event where SSAFY members from all over the country gather to enjoy together. However, due to the worsening COVID-19 situation, the meetup event, which used to be held offline, has been changed to a **non-face-to-face format through YouTube live streaming**.

The non-face-to-face event through YouTube has the advantage that SSAFY members nationwide can participate from anywhere regardless of location. However, since participants are not facing each other, **it is difficult to observe the various reactions of the trainees**, and because everything happens only on screen, **the sense of presence is lacking**, which reduces immersion in the event. Lastly, although it is a major event where SSAFY members from all over the country gather, there is only conversation between the host and trainees, making it **difficult for SSAFY trainees to communicate with each other**.

### **Expected Effects**

- Participants can indirectly experience **outdoor activities or face-to-face meetings** that they could not enjoy due to COVID-19 through the metaverse, relieving stress.  
- Unlike before, when they only watched YouTube videos, participants can feel as if they are actually at the event, leading to **improved immersion**.  
- **Interaction among SSAFY Meetup participants** can be more active than the previous comment-based communication method.  

<br/>

## Project Architecture

### Used Technologies

- Unity(2020.3.33f1)
- Plastic scm
- React.js(18.0.0)
- Photon cloud
- OpenVidu
- Spring boot(2.6.7)
- MySQL(8)
- Git
- AWS
- Jenkins
- Docker

![image-20220518103913472](README.assets/image-20220518103913472.png)

<br/>

## ⭐ Key Features
### Lobby
- When accessing SSAFYLand, users are directed to the lobby.  
- Users can enter their region, class, and name, and select a character.  
- When clicking "Start," a popup appears asking whether the user is a host. If the user is a host, they must enter the correct password.  
- Clicking the "Return to Main" button redirects back to the SSAFYLand webpage.  

![로비](README.assets/로비.gif)

### Stage

- A stage on the map where major events can be held.  
- PDFs required for the event can be opened and shared.  

![무대](README.assets/무대-16528374986168.gif)

### OX Game

- A true/false quiz game feature.  
- Participants can move to the correct side depending on the question, and based on whether they are correct or not, they either remain in the quiz area or are moved to another location. 

![OX](README.assets/OX-16528375045869.gif)

### Forest of Patience

- A game where players step on bricks and climb higher and higher.  
- A ranking system is implemented to determine who reaches the top first.  

![인내의숲](README.assets/인내의숲-165283750814010.gif)

### Treasure Hunt

- A feature where players can interact with objects to find treasures.  
- A ranking system is implemented to determine who finds the most treasures. 

![보물찾기](README.assets/보물찾기-165283751149711.gif)

### Exhibition Hall

- A place showcasing activities conducted at SSAFY.  
- By interacting with objects in front of each project, users can view the respective project.  

![전시관](README.assets/전시관-165283751513212.gif)

### Photo Zone

- A space where users can gather to take pictures together.  
- The current screen can be captured, and the captured image can be saved as a file.  

![포토존](README.assets/포토존-165283754153413.gif)

<br/>

### Additional Features

> Chat Feature

- Users can communicate using a global chat function.  

> Avatar Emotion Expression Feature

- When clicking a button that matches an emotion, the user’s character can express that corresponding emotion.  

> Map Feature  
- Displays the entire world map and shows the user’s current location.  
- By clicking the "Move to Main Location" button, users can move directly to that place.  

<br/>

## ⚒️ Installation

```bash
# frontend
# dir /frontend
npm install
npm start
# frontend build
npm run build

# backend
# dir /backend
./gradlew clean build

docker-compose up -d --build --force-recreate
```

## 🗃️ Final Deliverables

### Mid-term Presentation 

[SSAFYLand\_중간발표.pdf](exec/SSAFYLand_%EC%A4%91%EA%B0%84%EB%B0%9C%ED%91%9C.pdf)

### Final Presentation  

[SSAFYLand\_최종발표.pdf](exec/SSAFYLand_%EC%B5%9C%EC%A2%85%EB%B0%9C%ED%91%9C.pdf)
