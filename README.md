VANI_AI_PROJECT/
├── app/                     
│   ├── __init__.py          # Makes 'app' a package
│   ├── main.py              # Main FastAPI entry point
│   ├── connection.py        # WebSocket manager (Room/Audience logic)
│   ├── processor.py         # Logic for Speechmatics & Translation
│   └── database.py          # (Future) User & Transcript storage
├── static/                  # All Frontend Files
│   ├── css/                 
│   │   └── style.css        /* Shared styles & Dark mode */
│   ├── js/                  
│   │   ├── api.js           /* WebSocket & Mic logic */
│   │   └── offline.js       /* Transformers.js logic */
│   ├── index.html           /* Landing & Login */
│   ├── dashboard.html       /* Role Selection (Speaker/Audience) */
│   ├── presenter.html       /* Speaker UI (Original index.html) */
│   └── audience.html        /* Listener UI */
├── .env                     # API Keys & Secrets
└── requirements.txt         # Python Dependencies