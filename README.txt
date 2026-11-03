SONIA NATYASUTRA — DARK VIBRANT THEME
==========================================

UPDATED WEBSITE
---------------
The requested changes are already applied:
- Home: blended hero video setup.
- About: stage photo section + SONIA NATYASUTRA academy-building photo section.
- Dance Forms: Dance in Motion photos.
- Programs: Learning photos + photos for every program, including Foundation.
- Contact: removed the "Visit the academy" photo section and the separate Visit section.
- All sample photos are intentionally easy to replace.

HOMEPAGE VIDEO — HOW TO REPLACE IT
----------------------------------
1. Open the "assets" folder.
2. Replace "dance-hero.mp4" with your own dance-performance MP4.
3. Keep the filename exactly "dance-hero.mp4".
4. Keep "dance-poster.jpg" as the fallback image.
5. The homepage already applies a dark gradient + blend mode so the video melts into the dark vibrant background.

If you want to use a different filename, open index.html and change:
assets/dance-hero.mp4

PHOTOS — HOW TO REPLACE THEM
----------------------------
The new photo sections use sample online photographs with assets/dance-poster.jpg as a local fallback.
To use your own photographs, replace the URL in the corresponding style="background-image:..." with:
url('assets/your-photo.jpg'),url('assets/dance-poster.jpg')

Recommended local photo names:
- about-stage-1.jpg ... about-stage-4.jpg
- academy-building.jpg
- dance-motion-1.jpg ... dance-motion-3.jpg
- learning-1.jpg ... learning-3.jpg
- foundation.jpg
- intermediate.jpg
- advanced.jpg
- young-natya.jpg
- performance-lab.jpg
- private-mentoring.jpg

SOCIAL ICONS
------------
Replace the WhatsApp, Instagram and Facebook href="#" values with your real profile links.
