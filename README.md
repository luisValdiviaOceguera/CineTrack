# CineTrack
# 🎬 CineTrack

**Discover movies. Explore details. Keep track of your favorites.**

CineTrack is a native iOS application built with **SwiftUI** that allows users to discover movies, explore detailed movie information, read reviews, watch trailers, and manage their favorite titles.

The app integrates with a movie database API to deliver movie-related content through a modern, intuitive, and responsive user interface. It was developed with a focus on clean architecture, code reusability, and maintainability.

## ✨ Features

- **Movie Discovery:** Browse movies and explore their information.
- **Movie Details:** View movie descriptions, ratings, genres, release dates, and other relevant information.
- **Reviews:** Explore reviews to learn more about each movie.
- **Favorites Management:** Add and remove movies from your personal favorites list.
- **User Profile:** Access your profile and account-related information.
- **Authentication Flow:** Navigate through the onboarding and authentication experience.
- **Asynchronous Networking:** Fetch movie data efficiently using modern Swift concurrency.
- **Dynamic UI Updates:** Keep the interface synchronized with application state.

## 🛠️ Tech Stack

| Technology | Purpose |
|---|---|
| Swift | Primary programming language |
| SwiftUI | Declarative user interface |
| MVVM | Separation of UI, presentation logic, and data |
| URLSession | HTTP networking and API communication |
| async/await | Modern asynchronous programming |
| Codable | JSON encoding and decoding |
| Dependency Injection | Decoupled and testable components |
| Environment Objects | Shared application state |
| REST API | Remote movie data integration |

## 🏗️ Architecture & Design Patterns

CineTrack follows the **Model-View-ViewModel (MVVM)** architectural pattern to separate responsibilities and improve maintainability.

- **Model:** Represents movie data and other domain entities.
- **View:** Builds the user interface using reusable SwiftUI components.
- **ViewModel:** Handles presentation logic, manages UI state, and coordinates data requests.
- **Dependency Injection:** Provides dependencies to components instead of tightly coupling them to concrete implementations.
- **Service Layer:** Encapsulates API communication and networking responsibilities.
- **Asynchronous Programming:** Uses Swift's `async/await` to handle network requests with readable, structured code.

This approach promotes separation of concerns, testability, and scalability.

## 🌐 API Integration

CineTrack communicates with a movie database API to retrieve movie-related information, including:

- Movie details and metadata
- Ratings and reviews
- Trailer information
- Data used to populate movie discovery and favorites screens

Networking is implemented using `URLSession`, with `async/await` for asynchronous requests and `Codable` for decoding JSON responses into Swift models.

> **Note:** Update this section with the exact API provider and documentation link used in your project.

## 📱 Screens & User Experience

The application is organized around a movie discovery and management experience, allowing users to navigate between movie content, personal favorites, and profile information.

Potential screenshots to showcase in this section:

- Home / Movie Discovery
- Movie Details
- Reviews
- Favorites
- Movie Trailer
- User Profile

_Add screenshots or GIFs here to demonstrate the application in action._

## 🚀 Getting Started

### Prerequisites

- A Mac with Xcode installed
- An iOS Simulator or compatible iOS device
- API credentials, if required by the configured movie database service

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/luisValdiviaOceguera/CineTrack.git
   ```

2. Open the project in Xcode.

3. Configure the required API credentials according to the project's configuration.

4. Select an iOS Simulator or a compatible device.

5. Build and run the application.

## 🎯 Project Goals

CineTrack was developed to demonstrate practical iOS development skills, including:

- Building native interfaces with SwiftUI.
- Applying MVVM architecture and dependency injection.
- Integrating REST APIs using `URLSession`.
- Managing asynchronous operations with Swift concurrency.
- Modeling and decoding API responses using `Codable`.
- Building reusable and maintainable application components.
- Managing application state and user interactions.

## 🔮 Future Improvements

- Add unit tests for ViewModels and networking services.
- Improve offline support and local data persistence.
- Add advanced movie search and filtering.
- Enhance accessibility and Dynamic Type support.
- Introduce continuous integration and automated quality checks.

## Screenshots

<img width="353" height="727" alt="image" src="https://github.com/user-attachments/assets/97ab6c3e-3b5e-401d-9c18-9e8960b3e681" />
<img width="346" height="739" alt="image" src="https://github.com/user-attachments/assets/b3b1de8c-3618-4f83-82af-0feee5d6d674" />
<img width="354" height="732" alt="image" src="https://github.com/user-attachments/assets/d0a862b7-6a49-43a4-98aa-7dd34791dd57" />
<img width="357" height="745" alt="image" src="https://github.com/user-attachments/assets/9cbe18ff-3b3d-4aa0-8913-2c5a4d073cf6" />
<img width="349" height="738" alt="image" src="https://github.com/user-attachments/assets/ceb635a2-f028-4574-bce1-9d0417b5fa6c" />
<img width="355" height="745" alt="image" src="https://github.com/user-attachments/assets/865bf347-f3dc-4efe-b345-a3be80afd90e" />
<img width="352" height="741" alt="image" src="https://github.com/user-attachments/assets/44ec48be-5011-4db6-9542-f292a4041b8b" />


## 👨‍💻 Author

**Luis Valdivia**  
iOS Developer | Swift · SwiftUI · MVVM


