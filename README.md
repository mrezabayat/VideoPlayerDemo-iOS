# Video Player Demo (iOS)

## Overview
Video Player Demo is an iOS app built using **SwiftUI** and **AVPlayer**. It fetches videos from the [**Pexels API**](https://www.pexels.com/api/) and displays them in a grid of video cards. Users can tap on a video to play it in a full-screen player.

## Features
- Fetches and displays videos from the [**Pexels API**](https://www.pexels.com/api/).
- Uses **AVPlayer** to stream and play videos.
- SwiftUI-based UI with smooth animations.
- Supports portrait and landscape mode.

## Screenshots
*(Add screenshots of your app here)*

## Technologies Used
- **SwiftUI** for UI components
- **AVPlayer** for video playback
- **URLSession** for API requests
- **Async/Await** for efficient networking

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/video-player-demo.git
   ```
2. Open `VideoPlayerDemo.xcodeproj` in **Xcode**.
3. Replace `PEXELS_API_KEY` in `VideoManager.swift` with your **Pexels API Key**.
4. Build and run the project on a simulator or real device.

## Usage
- Launch the app.
- Browse videos in the grid layout.
- Tap on a video to play it in full-screen mode.

## API Key Setup
1. Sign up at [Pexels API](https://www.pexels.com/api/) to get an API key.
2. Replace `MY_API` in:
   ```swift
   urlRequest.setValue("PEXELS_API_KEY", forHTTPHeaderField: "Authorization")
   ```

## Requirements
- iOS 15+
- Xcode 14+
- Swift 5+

## Future Improvements
- Add video download functionality.
- Implement search feature for videos.
- Improve UI with more animations.

## License
This project is licensed under the **MIT License**.

---

### Author
Developed by **Mohammad Reza Bayat**

📧 Contact: [mrb.bayat@gmail.com](mailto:mrb.bayat@gmail.com)
💼 LinkedIn: [LinkedIn](https://linkedin.com/in/mrbayat)

