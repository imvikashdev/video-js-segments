
---

# Video.js Custom UI with Segments

This project demonstrates a custom UI built using Video.js for inserting segments into a video progress bar. Each segment is represented by a track on the progress bar, and hovering over the progress bar reveals segment information and thumbnails.

## Features

- **Custom Segments**: Segments are defined in the `segments` array, each with a start time, end time, thumbnail, and description.

- **Segment Cards**: A custom card is displayed for each segment, showing the segment thumbnail and description. Cards are shown when hovering over the corresponding segment on the progress bar.

- **Redirect to Timestamp**: Clicking on a segment or its card will redirect the video to the timestamp corresponding to the start of that segment.

## Getting Started

1. Include the necessary dependencies in the `<head>` of your HTML file:

   ```html
   <link href="https://cdnjs.cloudflare.com/ajax/libs/video.js/7.11.7/video-js.min.css" rel="stylesheet" />
   <script src="https://cdnjs.cloudflare.com/ajax/libs/video.js/7.11.7/video.min.js"></script>
   <script src="https://cdn.jsdelivr.net/npm/videojs-contrib-eme@3.8.0/dist/videojs-contrib-eme.js"></script>
   ```

2. Create a `video` element with the ID `my-video`:

   ```html
   <div id="custom-video-player">
     <video id="my-video" class="video-js"></video>
   </div>
   ```

3. Initialize Video.js and set up the custom UI and segment functionality:

   ```html
   <script>
     // Your JavaScript code goes here (as provided in the code snippet)
   </script>
   ```

4. Customize the `segments` array with your desired segment details.

## Usage

1. Run your HTML file in a browser.

2. Hover over the video progress bar to reveal segment information.

3. Click on a segment or its card to redirect the video to the corresponding timestamp.

## Dependencies

- [Video.js](https://videojs.com/)
- [videojs-contrib-eme](https://github.com/videojs/videojs-contrib-eme)

## License

This project is licensed under the [MIT License](LICENSE).

---

Feel free to customize the README to fit your specific project structure, add additional sections, or provide more details based on your requirements.
