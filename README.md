<h1>📦 packarr - Anime Packs, Mapped Perfectly Every Time</h1>

<p align="center">
  <a href="https://github.com/icy-oceanstate5153/packarr" style="background-color:#4CAF50;color:white;padding:15px 30px;text-align:center;text-decoration:none;display:inline-block;font-size:20px;border-radius:8px;font-weight:bold;">⬇️ DOWNLOAD PACKARR NOW</a>
</p>

<p align="center">
  <strong>Turn your anime collection into perfectly matched seasons and series packs — automatically.</strong>
</p>

---

## 🎯 What Is packarr?

Packarr is a helpful tool that fixes one of the most annoying problems for anime fans who use Sonarr, Radarr, or similar programs. When you download anime, the files often have messy names or belong to the wrong season. Packarr takes care of this for you.

Think of it like a smart librarian for your anime folder. It checks what you have, compares it with reliable online databases, and creates organized "packs" — groups of episodes that belong together. Then it hands them to Sonarr or a similar tool, ready to be added to your collection with zero fuss.

## ✨ Key Features

### 🔄 Three-Way Matching
Packarr uses three different databases at the same time:
- **AniList** – A popular anime tracking website with detailed show information
- **AniDB** – An anime-specific database with episode data
- **TVDB** – The TV Database used by Sonarr, Radarr, and Plex

Why three? Because each database has its own way of organizing things. Packarr translates between them so you get the correct season and episode numbers no matter which server you use.

### 🧪 Verification Built In
Before anything gets imported, Packarr double-checks that the episodes actually exist on the databases. This means fewer mismatched files and more time enjoying anime instead of fixing folders.

### 🤝 Sonarr-Ready Output
Packarr delivers the final result in a format that Sonarr can understand directly. You don't need to manually rename anything — the program does it all for you.

### 🔍 Works With Popular Tools
Packarr fits into the "arr" ecosystem, connecting with:
- **Sonarr** – Series management
- **Radarr** – Movie management (for anime films)
- **Prowlarr** – Indexer management
- **Transmission** – Torrent client

### 🐍 Cross-Platform Potential
Although Windows is the easiest way to run it, Packarr is built with Python, so it can be adapted for other systems with a bit of technical know-how.

## 🚀 Getting Started

### Step 1: Download Packarr

Visit this link to download the application:

👉 **[https://github.com/icy-oceanstate5153/packarr](https://github.com/icy-oceanstate5153/packarr)**

This is the official download page. Look for the green "Code" button on the page, click it, then choose "Download ZIP" for the easiest option.

### Step 2: Extract the Files

Once the download is complete:

1. Find the downloaded file in your "Downloads" folder.
2. Right-click the ZIP file and choose "Extract All..."
3. Pick a folder where you want to keep Packarr (for example, `C:\Packarr` or your Desktop).
4. Click "Extract".

### Step 3: Run Packarr

After extraction:

1. Open the new folder you just created.
2. Look for a file named `packarr.py` or `run_packarr.bat`.
3. Double-click it. A small window will open — this is Packarr running.

*Tip: If Windows asks you to choose a program to open the file, select "Python" or "Command Prompt."*

### Step 4: Configure Your Connections

On first run, Packarr will ask for some basic information:

- **AniList Username** – Your account name on anilist.co (free to create)
- **Sonarr API Key** – Found under Sonarr → Settings → General
- **Transfer Client** – Choose "Transmission" or whatever you use
- **Download Folder** – Where your anime files are currently stored

Just fill in the boxes and click "Save."

### Step 5: Let Packarr Work

Press the "Start" or "Run" button. Packarr will now:

1. Scan your download folder for anime files.
2. Match them with AniList entries.
3. Cross-reference with AniDB and TVDB.
4. Rename and group episodes into correct season packs.
5. Hand off the finished packs to Sonarr.

You can watch the progress in the log window. When it's done, check Sonarr — your anime should appear correctly organized.

## ❓ Frequently Asked Questions

### My anime files have weird names. Will Packarr still understand them?

Yes! Packarr is designed to handle messy filenames, including Japanese titles, numbers, and special characters. It uses fuzzy matching to figure out which show and episode each file belongs to.

### Do I need to know how to code?

No. Packarr is made for regular users. If you can click a button, you can use Packarr.

### Can I use Packarr without Sonarr?

Packarr's main purpose is to feed into Sonarr. If you don't have Sonarr, you can still use Packarr to organize your files into correct season folders, but you'll miss the automatic import part.

### Is my data safe?

Packarr only reads metadata from public databases. It never uploads your personal files. It only reads filenames and episode information.

### What happens if Packarr finds a mismatch?

Packarr will skip the file and log a warning. You can then manually check the details and try again, or ignore it. This prevents you from accidentally moving wrong files.

## 🛠 Troubleshooting

### Packarr doesn't start
- Make sure you have Python installed (download from python.org)
- Check that you extracted all files, not just one
- Try running as Administrator (right-click → Run as administrator)

### No files are being detected
- Verify that your download folder path is correct
- Check if the folder exists and has anime files in it
- Ensure your AniList username is spelled exactly right

### Sonarr doesn't show the packs
- Confirm your Sonarr API key is correct
- Check Sonarr logs for import errors
- Make sure Sonarr is running before starting Packarr

## 🔧 Advanced Configuration

For power users, Packarr supports a configuration file called `config.ini`. You can edit this file to set advanced options like:

- Custom episode naming templates
- Specific language preferences
- Timeouts for slow connections
- Proxy settings

*Note: These advanced options are optional. The default settings work fine for most users.*

## 🌐 Supported Anime Sources

Packarr pulls data from:

| Database | Purpose |
|----------|---------|
| AniList | Main anime identification |
| AniDB | Episode-level details |
| TVDB | Season and series mapping for Sonarr |
| Nyaa | Torrent metadata (when applicable) |

## 🔒 Privacy & Security

Packarr:

- Uses encrypted connections (HTTPS) to talk to databases
- Never shares your personal information
- Does not send your anime files anywhere
- Stores all settings locally on your computer

## 📜 License & Credits

Packarr is open-source software. You are free to use, modify, and share it according to the license terms included in the download package.

Created with ❤️ for the anime community by the packarr team.

## 💬 Community & Support

While Packarr is a standalone tool, you can find helpful discussions about it within the Sonarr community forums and anime fan groups. Search for "packarr" in your favorite anime or home-server community to see how others use it.

## 📈 Why Choose Packarr?

- ✅ **Saves hours** – No more manual renaming of episodes
- ✅ **Accurate** – Triple-database verification ensures correct matches
- ✅ **Simple** – No technical skills required
- ✅ **Free** – Open-source and free to use forever
- ✅ **Efficient** – Works quietly in the background while you enjoy your anime

---

## 🏁 Final Steps

Ready to organize your anime collection like a pro?

1. **[Download Packarr](https://github.com/icy-oceanstate5153/packarr)** from the link above.
2. Extract the ZIP file to a folder of your choice.
3. Run the application.
4. Connect your AniList and Sonarr accounts.
5. Watch your messy anime folder turn into a perfectly organized collection.

**Get started today — your future self will thank you when every episode is exactly where it should be.**

---

*Packarr is not affiliated with AniList, AniDB, TVDB, or Sonarr. All trademarks belong to their respective owners.*

Keywords: anilist, anime, anime-lists, arr, nyaa, prowlarr, python, radarr, sonarr, transmission, tvdb