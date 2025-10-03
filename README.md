🐷🕷️ SpiderPig

SpiderPig is a maintained fork of the original SpiderFoot OSINT automation tool.
It collects, correlates, and visualizes open-source intelligence from dozens of sources to help with investigations, red teaming, and security research.

✨ Features
🧩 Modular design: Write your own modules to pull from APIs, scrape sources, or enrich data.
🔎 Event-driven OSINT engine: Domains, IPs, emails, and more feed into a web of data.
📊 Visualization: Map relationships between targets in real-time.
🐷 Fresh modules: Community-driven integrations with modern APIs and data feeds.
🐍 Python 3.x support: Regularly updated dependencies for security and stability.
🚀 Getting Started
Installation

Clone the repo:

git clone https://github.com/<your-username>/spiderpig.git
<br>
cd spiderpig


Install requirements (it is recommended to use a virtualenv especially if you're on a debian based distro):

pip install -r requirements.txt

Run
python3 sf.py -l 127.0.0.1:5001


Then open your browser at http://127.0.0.1:5001.

🧑‍💻 Writing Your Own Modules

SpiderPig modules live in modules/ and are easy to extend. Each module listens for certain events (like DOMAIN_NAME) and produces new ones (like IP_ADDRESS).

Check out docs/MODULES.md for a quickstart guide.

🗺️ Roadmap
🚧  Upgrade Python dependencies
🚧  Docker support
🚧 Add new modules (suggestions are always welcome)
🚧 Improve reporting and export options
🚧 Re-skin web UI
🙌 Contributing

Pull requests are welcome! Feel free to open issues for bugs, ideas, or new integrations.

⚖️ License

SpiderPig is released under the same license as SpiderFoot (MIT).
Please credit the original author when referencing SpiderFoot.

🐖 Why "SpiderPig"?

Because like SpiderFoot, it sniffs around the web…
…but does it with a sense of humor 🐷🕷️
