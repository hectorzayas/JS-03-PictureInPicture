# Picture In Picture Enhanced Documentation

![](https://github.com/hectorzayas/JS-03-PictureInPicture/blob/master/PictureInPicture-min.gif)

## Overview
The **Picture In Picture** project leverages the Screen Capture API, specifically utilizing its `getDisplayMedia()` function, to facilitate the capture of either a portion or the entirety of a screen. This capability is crucial for functionalities such as streaming, recording, or sharing screen content. The captured content can then be displayed in a versatile Picture In Picture (PiP) window, which users can conveniently position anywhere on their screen. This initiative extends the foundational principles explored in the [javascript20-projects](https://github.com/zero-to-mastery/javascript20-projects) series.

### [Live Demonstration](https://hectorzayas.github.io/JS-03-PictureInPicture/)

## Features
- **Screen Capture API Utilization**: Empowers users to stream their recording sessions on the web application, enabling the creation of a dynamic Picture In Picture (PiP) display.

## Employed Tools
- **Screen Capture API**: [official documentation](https://developer.mozilla.org/en-US/docs/Web/API/Screen_Capture_API/Using_Screen_Capture).
- **CSS Only Shimmer Button**: [CSS Button](https://www.buttons.cool/button/gOqNxRa).
- **Google Fonts**: [Google Fonts](https://fonts.google.com/).

## Implementation Insights

### Styling with CSS
- The project incorporates a custom-designed CSS theme for both the web page's background and the button styling, showcasing a cohesive and visually appealing interface.

### Efficient API Integration
- The integration process makes extensive use of asynchronous programming, utilizing async functions and the await operator to ensure compatibility across various browsers.
- The user experience is streamlined through a user interface prompt, allowing users to select the desired screen area for sharing. The function `selectMediaStream()` is employed in this process, ultimately returning a `MediaStream` object that contains the captured display content.

## Acknowledgments
Special thanks to Jacinto Wong for providing the source code and inspiration for this project. [Jacinto Wong](https://github.com/JacintoDesign/)
