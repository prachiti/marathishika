# मराठी शिका - Learn Marathi App

A Progressive Web App (PWA) for learning Marathi from alphabets to conversations.

## 🚀 Deploy to Vercel

### Method 1: Using Vercel CLI (Recommended)

1. **Install Vercel CLI**
   ```bash
   npm install -g vercel
   ```

2. **Navigate to your project folder**
   ```bash
   cd /path/to/your/marathi-app
   ```

3. **Deploy**
   ```bash
   vercel
   ```

4. **Follow the prompts:**
   - Login to Vercel (if not already)
   - Set up and deploy (just press Enter for defaults)
   - Done! You'll get a URL like: `https://marathi-app.vercel.app`

### Method 2: Using Vercel Dashboard (Easiest)

1. **Go to:** https://vercel.com

2. **Sign up/Login** (free account)

3. **Click "Add New" → "Project"**

4. **Import from Git:**
   - If using GitHub/GitLab:
     - Connect your repository
     - Select the repo
     - Click "Deploy"
   
   - If uploading files directly:
     - Drag and drop your folder
     - Or upload the 3 files:
       - `marathi-with-profiles.html`
       - `manifest.json`
       - `sw.js`

5. **Configure (optional):**
   - Project Name: `marathi-app`
   - Framework Preset: Other
   - Root Directory: `./`

6. **Click "Deploy"**

7. **Done!** You'll get a URL like: `https://marathi-app.vercel.app`

### Method 3: Drag & Drop (Simplest!)

1. Go to: https://vercel.com/new

2. **Drag and drop your folder** with all files

3. Click **"Deploy"**

4. Wait 30 seconds - Done! ✅

---

## 📁 Files Needed

Make sure you have these 3 files in your folder:
- ✅ `marathi-with-profiles.html` (main app)
- ✅ `manifest.json` (PWA config)
- ✅ `sw.js` (service worker)

---

## ⚙️ Optional: Rename index.html

For cleaner URLs, rename the main file:

```bash
mv marathi-with-profiles.html index.html
```

Then update `manifest.json`:
```json
"start_url": "./index.html"
```

And `sw.js`:
```javascript
const urlsToCache = [
  './index.html',
  './manifest.json'
];
```

Now your app will be accessible at: `https://your-app.vercel.app/` instead of `https://your-app.vercel.app/marathi-with-profiles.html`

---

## 🌐 Custom Domain (Optional)

After deployment:
1. Go to project settings
2. Click "Domains"
3. Add your custom domain (e.g., `learn-marathi.com`)
4. Follow DNS setup instructions

---

## 🔄 Updates

To update your app:
- Just push changes to Git, or
- Redeploy through Vercel dashboard
- Changes go live instantly!

---

## ✅ After Deployment

Your app will be available at:
- 🌐 Web: `https://your-app.vercel.app`
- 📱 iOS: Open in Safari → Share → Add to Home Screen
- 📱 Android: Open in Chrome → Install App

---

## 📊 Features

- ✅ 21 progressive lessons
- ✅ Multiple user profiles
- ✅ Offline support (PWA)
- ✅ Progress tracking
- ✅ Gamification (XP, streaks)
- ✅ Works on all devices

---

## 🆘 Troubleshooting

**Issue: PWA not working**
- Make sure all 3 files are in the same folder
- Check browser console for errors
- Try in incognito mode

**Issue: Service worker not registering**
- Vercel serves files with HTTPS (required for PWA)
- Clear browser cache and reload

**Issue: Can't see changes**
- Clear browser cache
- Force reload: Ctrl+Shift+R (Windows) or Cmd+Shift+R (Mac)

---

## 📞 Support

For issues or questions, check the files are properly uploaded and HTTPS is enabled (Vercel does this automatically).

---

**Enjoy learning Marathi! 🦉 मराठी शिका**
