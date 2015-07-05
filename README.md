# ruraltel

prompts are in /var/lib/asterisk/sounds/prompts/

prompts/
├── comupdates
│   ├── eng-comupdates-press3.mp3
│   ├── hin-comupdates-press3.mp3
│   └── tib-comupdates-press3.mp3
├── language
│   ├── eng-lang-press1.mp3
│   ├── hin-lang-press3.mp3
│   └── tib-lang-press2.mp3
├── record
│   ├── eng-rec-press1.mp3
│   ├── hin-rec-press1.mp3
│   └── tib-rec-press1.mp3
├── weather
│   ├── eng-weather-press2.mp3
│   ├── hin-weather-press2.mp3
│   └── tib-weather-press2.mp3
└── welcome
    ├── eng-welcome.mp3
    ├── hin-welcome.mp3
    └── tib-welcome.mp3

weather and community updates are uploaded to /var/lib/asterisk/sounds/updates/

updates/
├── tib-comm-update.mp3
└── tib-weather-report.mp3

recordings are located to /var/lib/asterisk/sounds/recording/


Files must be owned by the User and Group Asterisk

	chown asterisk:asterisk file.mp3
