
# Question 1
A software training institute is developing a webpage to promote its **Programming Bootcamp**. The webpage should introduce the course, explain important web development terms, showcase multimedia content, display the campus location, and provide basic registration status information using appropriate HTML elements.

Create the webpage according to the requirements below. Use the specified HTML elements, text, attributes, attribute values, and content exactly where stated.

## Task

### 1. Document Setup

- Use the HTML5 document type declaration.
- Set the `<html>` element's `lang` attribute to exactly `en`.
- Set the page title to exactly `Programming Bootcamp`.
- Include a UTF-8 character encoding declaration.

### 2. Bootcamp Title

- Add exactly one Level 1 heading (`<h1>`) with the text `HTML Programming Bootcamp`.
- Immediately after the `<h1>`, add exactly one Level 2 heading (`<h2>`) with the text `Learn Modern Web Development from Scratch`.

### 3. Course Overview

- Add a Level 3 heading (`<h3>`) with the text `Course Overview`.
- Immediately after the heading, add one paragraph (`<p>`).
- The paragraph must contain the following:
  - The word `HTML` must be highlighted using the `<mark>` element.
  - The text `HTML 4` must be displayed as deleted text using the `<del>` element.
  - The text `HTML5` must be displayed as inserted text using the `<ins>` element.
  - Include the statement that students will complete `10²` practice exercises. The `2` must use the `<sup>` element.
  - Include the chemical formula `H₂O`. The `2` must use the `<sub>` element.
- The paragraph must contain this exact wording:

  `This bootcamp is designed to help students become professional web developers by learning HTML, CSS, JavaScript, and modern development tools. HTML 4 HTML5 provides many new features for building modern websites. Students will complete 10² practice exercises throughout the course. Even a simple formula like H₂O demonstrates the use of subscript text.`

- Add a horizontal rule (`<hr>`) immediately after the paragraph.

### 4. Course Terms

- Add a Level 3 heading (`<h3>`) with the text `Course Terms`.
- Create exactly one description list using `<dl>`.
- Add the following three terms using `<dt>` and their corresponding definitions using `<dd>`, in the same order:

  **Term:** `HTML`  
  **Definition:** `Defines the structure of a webpage.`

  **Term:** `CSS`  
  **Definition:** `Styles and designs webpages.`

  **Term:** `JavaScript`  
  **Definition:** `Adds interactivity and dynamic behavior to webpages.`

- Do not use an unordered list, ordered list, or table for these terms.
- Add a horizontal rule (`<hr>`) immediately after the description list.

### 5. Course Introduction Video

- Add a Level 3 heading (`<h3>`) with the text `Course Introduction Video`.
- Add exactly one `<video>` element.
- The video must:
  - Have playback controls enabled.
  - Have its `width` attribute set to exactly `500`.
  - Contain a `<source>` element.
  - Use `bootcamp.mp4` as the source file.
  - Set the source `type` attribute to exactly `video/mp4`.
  - Display the fallback text `Your browser does not support the video element.`
- Add a horizontal rule (`<hr>`) immediately after the video.

### 6. Welcome Audio

- Add a Level 3 heading (`<h3>`) with the text `Welcome Audio`.
- Add exactly one `<audio>` element.
- The audio must:
  - Have playback controls enabled.
  - Contain a `<source>` element.
  - Use `welcome.mp3` as the source file.
  - Set the source `type` attribute to exactly `audio/mpeg`.
  - Display the fallback text `Your browser does not support the audio element.`
- Add a horizontal rule (`<hr>`) immediately after the audio.

### 7. Campus Location

- Add a Level 3 heading (`<h3>`) with the text `Campus Location`.
- Add exactly one `<iframe>` for the Google Maps location.
- Set the iframe `src` attribute to exactly:

  `https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3153.086611!`

- Set the `width` attribute to exactly `500`.
- Set the `height` attribute to exactly `300`.
- Include the `allowfullscreen` attribute.
- Set the `loading` attribute to exactly `lazy`.
- Do not add any other iframe attributes.
- Add a horizontal rule (`<hr>`) immediately after the Google Maps iframe.

### 8. Watch on YouTube

- Add a Level 3 heading (`<h3>`) with the text `Watch on YouTube`.
- Add exactly one `<iframe>` for the YouTube video.
- Set the `width` attribute to exactly `500`.
- Set the `height` attribute to exactly `300`.
- Set the `src` attribute to exactly:

  `https://www.youtube.com/embed/dQw4w9WgXcQ`

- Set the `title` attribute to exactly `Programming Bootcamp`.
- Include the `allowfullscreen` attribute.
- Do not add any other iframe attributes.
- Add a horizontal rule (`<hr>`) immediately after the YouTube iframe.

### 9. Student Registration Status

- Add a Level 3 heading (`<h3>`) with the text `Student Registration Status`.

#### Registration Status

- Add exactly one text input.
- Set its `type` attribute to exactly `text`.
- Set its `value` attribute to exactly `Registration Closed`.
- Make the input disabled so that the user cannot edit its value.
- Do not add any other attributes to this input.

#### Course Updates

- Add exactly one checkbox.
- Make the checkbox selected by default.
- Use a `<label>` element for the checkbox.
- The label must display exactly `Receive Course Updates`.
- Do not add any other form controls.

### 10. Required Section Order

The sections must appear in this exact order:

1. Bootcamp title
2. Course Overview
3. Course Terms
4. Course Introduction Video
5. Welcome Audio
6. Campus Location
7. Watch on YouTube
8. Student Registration Status

Within each section, follow the element order specified in its requirements.

## Output

![alt text](<Screenshot 2026-10-27 at 11.40.57 AM.png>)

# Question 2

Create a personal portfolio webpage that introduces you to visitors. Organize the content into a clean and meaningful webpage using appropriate HTML elements.

## Task
Create the webpage that satisfies the following requirements:

### Portfolio Header
* Create an appropriate page title.
* Add an HTML comment to identify this section as `Portfolio Header`.
* Display your name as a Level 1 Heading (`<h1>`).
* Display your career goal or designation (Example: Aspiring Web Developer) as a Level 2 Heading (`<h2>`).

### About Me
* Add an HTML comment to identify this section as `About Me`.
* Display **About Me** as a Level 3 Heading (`<h3>`).
* Create a paragraph introducing yourself. The paragraph should include:
  * Your educational background.
  * Your interests.
  * The technologies you are currently learning.
  * Your career goal.
* Within the paragraph:
  * Highlight the names of at least three technologies.
  * Emphasize one sentence that describes your learning attitude.
* Insert a horizontal line after this section.

### Technical Skills
* Add an HTML comment to identify this section as `Technical Skills`.
* Display **Technical Skills** as a Level 3 Heading (`<h3>`).
* Display at least five technical skills of your choice as an unordered list.
* Insert a horizontal line after this section.

### Learning Journey
* Add an HTML comment to identify this section as `Learning Journey`.
* Display **Learning Journey** as a Level 3 Heading (`<h3>`).
* Display at least five technologies or skills that you plan to learn in the future as an ordered list.
* Insert a horizontal line after this section.

### Projects
* Add an HTML comment to identify this section as `Projects`.
* Display **Projects** as a Level 3 Heading (`<h3>`).
* Display at least four projects that you have completed or would like to build as an unordered list.
* Insert a horizontal line after this section.

### Profile Picture
* Add an HTML comment to identify this section as `Profile Picture`.
* Display **Profile Picture** as a Level 3 Heading (`<h3>`).
* Display a profile picture.
* Add meaningful alternative text to the image.
* Display a short descriptive caption immediately below the image describing what the image represents.
* Insert a horizontal line after this section.

### Contact Me
* Add an HTML comment to identify this section as `Contact Me`.
* Display **Contact Me** as a Level 3 Heading (`<h3>`).
* Provide the following contact details:
  * A link to your GitHub profile. Display the link on a new line using a paragraph.
  * A link to your LinkedIn profile. Display the link on a new line using a paragraph.
  * An email link. Display the link on a new line using a paragraph.
  * A telephone link. Display the link on a new line using a paragraph.
* Ensure the GitHub and LinkedIn links open in a new browser tab.

#### Refer to the image below for the expected output.
![web-developer](https://eufiejefslcyrgminhag.supabase.co/storage/v1/object/public/content-assets/editor-images/8c9b81dc-f10c-4c68-abaf-dff0f5f7a7be/web-developer.jpeg)