# GenerativeMusic-InteractiveStudio
<b>This project was built using Max MSP, a visual programming language, and it is both a generative music system, as well as an interactive map in which the user can walk around the studio where the music is being recorded.</b>

<b>Full demo video available here: https://vimeo.com/598922725</b>

The generative system is based on 40 Logic Pro X loops for different instruments, which were carefully selected to sound musically coherent. This Max MSP patch then continuously orchestrates 4 different musical sections through a Markov Chain. Each section has multiple musical phrases for each instrument available, and the system decides which ones to play and for how long. Additionally, it triggers a drum fill before every section change and the music only stops when the user chooses so.

<img width="1792" alt="Screenshot 2021-09-07 at 15 57 32" src="https://user-images.githubusercontent.com/90060036/132366665-7a4419ec-3011-4fa4-be3b-aae6620fe985.png">
<img width="1792" alt="Screenshot 2021-09-07 at 15 58 14" src="https://user-images.githubusercontent.com/90060036/132366780-ca9cbb0b-7c03-4706-99a0-74021fb46e3d.png">

Regarding the interactive map, the user can walk around the studio and enter the different rooms - drum booth, guitar room, control room - and the sound changes depending on where they are, replicating the experience of being inside the studio, In the drum booth the user hears the drums being recorded, in the control room they hear the full mix with every instrument, while in the hallway they hear the sound from the closest room much quieter and filtered. A door sound is also triggered whenever the user enters/leaves a room.

<img width="1792" alt="Screenshot 2021-09-06 at 18 17 04" src="https://user-images.githubusercontent.com/90060036/132367281-cbfd939b-e737-4308-ac8d-be1a1865f5e9.png">
<img width="1792" alt="Screenshot 2021-09-07 at 16 00 20" src="https://user-images.githubusercontent.com/90060036/132367086-0bbb8265-06a2-43b8-b8ab-9ee290313007.png">
