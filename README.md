# 💬 Realtime Chat Application

A real-time chat application supporting multi-user messaging with dynamic room management and low-latency communication. Built with scalable architecture and optimized for concurrent sessions.

---

## 🚀 Features

- 🔗 WebSocket-based real-time communication
- 👥 Support for multiple users and chat rooms
- 🧠 Efficient message broadcasting
- 🛡️ Secure and optimized backend
- 🛠️ Built with Java and Spring Boot

---

## 🏗️ Tech Stack

- **Backend**: Java, Spring Boot, WebSocket
- **Build Tool**: Maven
- **Protocol**: STOMP over WebSocket
- **IDE**: IntelliJ IDEA / Eclipse

---

## 📁 Project Structure

```
Realtime-Chat-Application/
├── src/ # Java source files
│ └── main/
│ ├── java/
│ │ └── com/chatapp/
│ │ ├── controller/
│ │ ├── config/
│ │ ├── model/
│ │ ├── service/
│ │ └── ChatAppApplication.java
│ └── resources/
│ ├── static/
│ ├── templates/
│ └── application.properties
├── pom.xml # Maven configuration
├── mvnw, mvnw.cmd # Maven wrapper
├── README.md # Project README
```

---

## ⚙️ Setup Instructions

### Prerequisites

- Java 17 or above
- Maven 3.6+
- IDE (IntelliJ / Eclipse)

### Clone and Build

```bash
git clone https://github.com/yourusername/Realtime-Chat-Application.git
cd Realtime-Chat-Application
./mvnw clean install
```

### Run the Application

```
./mvnw spring-boot:run
```

---

## 📡 How It Works

- Client connects to the server using WebSocket (via STOMP protocol).
- Messages are routed through the server to appropriate chat rooms.
- All users in a room receive real-time updates instantly.

---

## 🧪 Testing

- Unit and integration tests can be written using JUnit and Mockito.
- To run tests:
```
./mvnw test
```
