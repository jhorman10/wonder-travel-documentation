# wonder-travel-documentation

Documentation of the wonder travel project structure

This project is a technical test for wonder travel, 
developed mainly for mobile view, it was created with vite and yarn, 
as a suggestion I recommend to update the NodeJS version,
update yarn and verify that you can make use of the yarn commands in the console. 

## Installation

1. Clone this repository: `git clone https://github.com/jhorman10/wonder-travel-frontend.git`.
2. Go to the project directory: `cd wonder-travel-frontend`.
3. Install the dependencies: `yarn`.

## Usage

landing page

## Project Structure

/wonder-travel-frontend  
<pre>
├── package.json  
├── public  
│   └── vite.svg  
├── src  
│   ├── App.css  
│   ├── App.jsx  
│   ├── api  
│   │   └── schedule.js  
│   ├── assets  
│   │   ├── fonts  
│   │   │   └── Proxima-Nova-Extra-Condensed  
│   │   │       └── Demo_Fonts  
│   │   │           ├── AbrilFatface-Regular.ttf  
│   │   │           ├── Fontspring-DEMO-proximanova-bold.otf  
│   │   │           ├── Fontspring-DEMO-proximanova-light.otf  
│   │   │           ├── Fontspring-DEMO-proximanova-medium.otf  
│   │   │           ├── Fontspring-DEMO-proximanova-regular.otf  
│   │   │           ├── Fontspring-DEMO-proximanova-semibold.otf  
│   │   ├── images  
│   │   │   ├── ACOTUR LOGO AI-01.png  
│   │   │   ├── ACOTUR LOGO AI-01@2x.png  
│   │   │   ├── ACOTUR LOGO AI-01@3x.png  
│   │   │   ├── Group 1098.svg  
│   │   │   ├── Group 1101.svg  
│   │   │   ├── Group 1185.svg  
│   │   │   ├── Group 431.svg  
│   │   │   ├── Group 470.png  
│   │   │   ├── Group 470@2x.png  
│   │   │   ├── Group 470@3x.png  
│   │   │   ├── Group 536.svg  
│   │   │   ├── Icon - Keyboard Arrow - Up - Dark.svg  
│   │   │   ├── Path 2202.svg  
│   │   │   ├── Path 2282-1.svg  
│   │   │   ├── Path 2282-2.svg  
│   │   │   ├── Path 2282-3.svg  
│   │   │   ├── Path 2282-4.svg  
│   │   │   ├── Path 2282-5.svg  
│   │   │   ├── Path 2282-6.svg  
│   │   │   ├── Path 2282-7.svg  
│   │   │   ├── Path 2282.svg  
│   │   │   ├── Path 2287.svg  
│   │   │   ├── Path 2388.svg  
│   │   │   ├── Path 2389.svg  
│   │   │   ├── Path_2202.png  
│   │   │   ├── amazonas (3).png  
│   │   │   ├── amazonas (3)@2x.png  
│   │   │   ├── amazonas (3)@3x.png  
│   │   │   ├── ballena (2).png  
│   │   │   ├── ballena (2)@2x.png  
│   │   │   ├── ballena (2)@3x.png  
│   │   │   ├── cerro-pajarito11-.png  
│   │   │   ├── cerro-pajarito11-@2x.png  
│   │   │   ├── cerro-pajarito11-@3x.png  
│   │   │   ├── montanas (1).png  
│   │   │   ├── montanas (1)@2x.png  
│   │   │   ├── montanas (1)@3x.png  
│   │   │   ├── noun_Cursor_1692870.svg  
│   │   │   ├── noun_Email_3715572.svg  
│   │   │   ├── noun_Food_2688587-1.svg  
│   │   │   ├── noun_Food_2688587-2.svg  
│   │   │   ├── noun_Food_2688587-3.svg  
│   │   │   ├── noun_Food_2688587.svg  
│   │   │   ├── noun_Hut_233351.svg  
│   │   │   ├── noun_Plane_2797956-1.svg  
│   │   │   ├── noun_Plane_2797956.svg  
│   │   │   ├── noun_adventure_1941281.svg  
│   │   │   ├── noun_adventure_68979.svg  
│   │   │   ├── noun_off-road_1938384.svg  
│   │   │   ├── noun_sleeping_947849-1.svg  
│   │   │   ├── noun_sleeping_947849-2.svg  
│   │   │   ├── noun_sleeping_947849.svg  
│   │   │   ├── puesta-de-sol.png  
│   │   │   ├── puesta-de-sol@2x.png  
│   │   │   ├── puesta-de-sol@3x.png  
│   │   │   ├── reciclar.png  
│   │   │   ├── reciclar@2x.png  
│   │   │   ├── reciclar@3x.png  
│   │   │   ├── tucan.png  
│   │   │   ├── tucan@2x.png  
│   │   │   ├── tucan@3x.png  
│   │   │   ├── viajero (1).png  
│   │   │   ├── viajero (1)@2x.png  
│   │   │   ├── viajero (1)@3x.png  
│   │   │   ├── viajero.png  
│   │   │   ├── viajero@2x.png  
│   │   │   ├── viajero@3x.png  
│   │   │   ├── whatsapp (1).png  
│   │   │   ├── whatsapp (1)@2x.png  
│   │   │   ├── whatsapp (1)@3x.png  
│   │   │   └── wondertravel.png  
│   │   └── react.svg  
│   ├── components  
│   │   ├── CardInfo  
│   │   │   └── index.jsx  
│   │   ├── Footer  
│   │   │   └── index.jsx  
│   │   ├── ScheduleDetails  
│   │   │   └── index.jsx  
│   │   ├── ScheduleStepper  
│   │   │   └── index.jsx  
│   │   ├── ScheduleSteps  
│   │   │   └── index.jsx  
│   │   └── index.js  
│   ├── database  
│   │   └── schedule.json  
│   ├── hooks  
│   │   ├── index.js  
│   │   ├── useImageSearch.js  
│   │   ├── useSchedule.js  
│   │   └── useWhatsAppChat.js  
│   ├── index.css  
│   ├── main.jsx  
│   └── pages  
│       ├── Contact  
│       │   └── index.jsx  
│       ├── ReserveInfo  
│       │   └── index.jsx  
│       ├── Schedule  
│       │   └── index.jsx  
│       └── index.js  
├── vite.config.js  
└── yarn.lock  
</pre>
  
## License

MIT License.

## Contact

jsojhor@gmail.com
