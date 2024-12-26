# **Image Sonification: Let's Hear the Galaxies! 🚀🎶**

## **Abstract**  
Ever wondered what galaxies *sound* like? This project bridges the gap between sight and sound, turning beautiful galaxy images into fascinating audio experiences. By analyzing the pixel data (RGB values) of galaxy images, we map colors and brightness into melodies, rhythms, and tones. Get ready to *hear* the stars and explore a whole new dimension of space exploration! 🌌✨  

---

## **Project Description**  
This repository is a playground for cosmic creativity! Here’s what it does:  

1. **Load Galaxy Images**: It all starts with a special `.npy` file containing galaxy images.  
2. **Pixel Exploration**: Dive deep into the RGB color data of these images.  
3. **Visualization**: View galaxies with OpenCV and matplotlib, and uncover hidden patterns using heatmaps.  
4. **Data Extraction**: Save all pixel information into a neat CSV file for analysis or further exploration.  
5. **Image Sonification**: Here's the magic – map visual data into audio by:  
   - Mapping **brightness** to pitch.  
   - Using the **red channel** to control volume.  
   - Translating **blue values** into sound duration.  

---

## **Creative Sound Mapping**  

### **1. RGB to Melody**  
- **Red, Green, and Blue** values are individually mapped to frequency ranges, creating unique tones:  
  - Red: Low notes 🎵  
  - Green: Mellow mids 🎼  
  - Blue: Bright highs 🎶  
- The result? A harmony of sine waves creating a cosmic symphony.  

### **2. Brightness to Pitch**  
- Bright pixels = higher pitch.  
- Dark pixels = deeper tones.  
- Together, they create a melodic representation of light and shadow.  

### **3. Red Channel as Volume**  
- Brighter red? Louder sound!  
- Dim red? Softer whispers.  

### **4. Blue Channel as Duration**  
- Blue decides how long each note plays.  
- Subtle blues linger, while bright blues are snappy!  

---

## **Project Structure**  

- **data/:** This is where the galaxy pictures are stored.
- **.ipynb:**  These are like digital notebooks where we write and run our code.
- **output/:**  This is where we save the color information and any pictures we create.
