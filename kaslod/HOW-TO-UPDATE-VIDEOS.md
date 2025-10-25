# 📹 How to Update YouTube Videos in ShredHub

## Paano Mag-update ng Videos

### Super Easy Method! 🎯

Open `kaslod.html` and find this section (around line 487):

```javascript
const featuredVideos = [
    {
        videoId: 'AkyempRzRL8',
        title: 'Alpine Descent',
        rider: 'Elena Rodriguez',
        location: 'Switzerland',
        distance: '8.2 miles',
        badge: { text: 'NEW', color: 'orange' }
    },
    // Add more videos here...
];
```

### Step 1: Get YouTube Video ID

From any YouTube URL like:
- `https://www.youtube.com/watch?v=dQw4w9WgxcQ`
- The video ID is: **dQw4w9WgxcQ**

### Step 2: Update the Array

Just change the `videoId`, `title`, `rider`, `location`, and `distance`:

```javascript
{
    videoId: 'YOUR_VIDEO_ID_HERE',
    title: 'Mountain Run',
    rider: 'Juan Dela Cruz',
    location: 'Baguio, Philippines',
    distance: '5.3 miles',
    badge: { text: 'NEW', color: 'orange' }
}
```

### Badge Colors Available:
- `'orange'` - Orange badge
- `'pink'` - Pink badge
- `'purple'` - Purple badge
- `'blue'` - Blue badge
- `'green'` - Green badge

### Badge Text Examples:
- `NEW` - For new videos
- `POPULAR` - For popular content
- `TRENDING` - For trending videos
- `TOP` - For top videos
- `FEATURED` - For featured content

### Adding More Videos:

Just add another object to the array:

```javascript
const featuredVideos = [
    {
        videoId: 'AkyempRzRL8',
        title: 'Alpine Descent',
        rider: 'Elena Rodriguez',
        location: 'Switzerland',
        distance: '8.2 miles',
        badge: { text: 'NEW', color: 'orange' }
    },
    {
        videoId: 'dQw4w9WgxcQ',
        title: 'Coastal Cruze',
        rider: 'Marcus Chen',
        location: 'California',
        distance: '5.6 miles',
        badge: { text: 'POPULAR', color: 'pink' }
    },
    {
        videoId: 'YOUR_NEW_VIDEO_ID',
        title: 'Your New Video',
        rider: 'Your Name',
        location: 'Your Location',
        distance: '3.2 miles',
        badge: { text: 'NEW', color: 'green' }
    }
];
```

## Features Included ✨

### 1. **Auto YouTube Thumbnails**
   - Thumbnails automatically load from YouTube
   - No need to download or upload images!

### 2. **Video Modal Player**
   - Click any video card to watch
   - Professional embedded YouTube player
   - Auto-play when opened

### 3. **Easy Controls**
   - Press **ESC** to close video
   - Click outside to close
   - Click "X" button to close

### 4. **Watch on YouTube Button**
   - Opens video in new tab
   - Direct link to YouTube

### 5. **Responsive Design**
   - Works on desktop, tablet, mobile
   - Smooth animations
   - Hover effects

### 6. **No API Key Needed!**
   - Free YouTube integration
   - No setup required
   - Just change the video IDs!

## YouTube Partnership Info 🤝

**Good News:** Hindi kailangan ng formal partnership with YouTube!

You can freely embed YouTube videos on your website using:
- ✅ YouTube IFrame Player API (what we're using)
- ✅ Free to use
- ✅ No API key required for basic embedding
- ✅ Thumbnails are publicly accessible

As long as the videos are:
1. Publicly available on YouTube
2. Not age-restricted
3. Embedding is allowed by the video owner

You're good to go! 🎉

## Troubleshooting

**Q: Video won't play?**
- Check if video is public
- Check if embedding is allowed
- Try a different video ID

**Q: Thumbnail not showing?**
- Video might be private
- Try a different video
- System will try fallback thumbnail automatically

**Q: How to test?**
- Just open `kaslod.html` in your browser
- Click on any video card
- Should open in modal and auto-play!

## Example Real Downhill Videos

Here are some great downhill skateboarding video IDs you can use:

```javascript
'AkyempRzRL8'  // Epic downhill run
'70ovFxDe9i8'  // Skateboarding compilation
'1k7jG3j3tlM'  // Action sports
```

---

**Need Help?** Just edit the `featuredVideos` array and refresh your browser! 🚀


