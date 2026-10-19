# Image Sampling and Aliasing — MATLAB

MATLAB implementations exploring spatial image sampling, subsampling, anti-aliasing, and aliasing artifacts. This project demonstrates how sampling rates and anti-aliasing filters affect image quality, as well as how spatial information can be embedded into an image and revealed through subsampling.

## Features

- **Image Sampling:** Uniformly subsamples images by selecting every \(D\)-th pixel in both spatial directions.
- **Anti-Aliasing:** Applies a spatial averaging filter before subsampling to reduce aliasing artifacts.
- **Sampling Comparisons:** Visualizes how different sampling factors affect image detail and appearance.
- **Magic Image:** Combines two grayscale images so that one is visible at full resolution while the other is revealed through uniform subsampling at \(D = 5\).
- **Video Sampling:** Explores the relationship between sampling frequency and apparent motion.

## Visual Results

### 1. Anti-Aliasing

Demonstrates the effect of spatial filtering on image quality and aliasing artifacts.

<img width="518" height="284" alt="Screenshot 2026-10-19 005914" src="https://github.com/user-attachments/assets/3cf34f9c-931e-47f6-9102-90236b0d18dc" />


### 2. Anti-Aliased Sampling — D = 2

Shows the effect of anti-aliasing followed by subsampling by a factor of 2 in both spatial directions.

<img width="528" height="260" alt="Screenshot 2026-10-19 005908" src="https://github.com/user-attachments/assets/0ccf336d-bfcd-4b8c-9aab-77562d7c330c" />


### 3. Image Sampling — D = 4

Demonstrates how a larger sampling factor affects spatial detail and image appearance.

<img width="507" height="251" alt="Screenshot 2026-10-19 005857" src="https://github.com/user-attachments/assets/a8dd9f77-8bd0-4418-80ff-e68f2c477204" />


### 4. Magic Image — D = 5

Demonstrates a two-image encoding technique in which the image revealed after uniform subsampling differs from the image visible at full

<img width="521" height="258" alt="Screenshot 2026-10-19 005837" src="https://github.com/user-attachments/assets/14376c67-ff43-4b14-8def-5278128fc128" />
