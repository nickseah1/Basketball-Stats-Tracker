# Basketball-Stats-Tracker
Application to track basketball statistics

basketball_stats_tracker/
├── app/
│   ├── __init__.py          # Initializes the app and its configurations
│   ├── routes.py            # Handles URL routing and request handling
│   ├── models.py            # Database models for stats and users
│   ├── forms.py             # Form handling (if required, e.g., for input validation)
│   ├── templates/           # HTML files for the frontend
│   │   ├── base.html        # Base template for consistent layout
│   │   ├── home.html        # Homepage showing games and stats
│   │   ├── game_entry.html  # Page for entering game stats
│   │   ├── stats.html       # Stats summary page
│   └── static/              # Static files like CSS, JS, and images
│       ├── css/
│       │   └── styles.css   # Custom styles
│       ├── js/
│       │   └── scripts.js   # Frontend functionality
│       └── images/          # App logos or images
├── migrations/              # Database migration files (if using Flask-Migrate)
├── tests/                   # Unit tests for the app
│   ├── __init__.py          # Initializes the test suite
│   └── test_app.py          # Test cases for routes and functionality
├── venv/                    # Virtual environment for dependencies (optional)
├── config.py                # Configuration settings (database, secrets)
├── requirements.txt         # List of Python dependencies
├── README.md                # Project overview and instructions
├── run.py                   # Main script to run the Flask/Django app

