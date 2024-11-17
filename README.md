# Shortn - URL Shortener

Shortn is a personal project to learn and practice Rust programming, utilizing the powerful `actix-web` framework to build a URL shortener service. This README will document the project's features, development, and progress.

## Features

Shortn is planned to include the following features:

### Core Features (To-Do)
- [ ] **URL Shortener**  
      Convert long URLs into short and shareable ones.

- [ ] **QR Code Generation**  
      Generate QR codes for the shortened URLs.

- [ ] **Rate Limiter (Per IP)**  
      Implement rate limiting to prevent abuse by setting a maximum request rate per IP.

- [ ] **Click Statistics**  
      Track the total number of clicks on each shortened URL.

- [ ] **Password-Protected Short URLs**  
      Allow users to lock their short URLs with a password.

- [ ] **Expiration-Based Short URLs**  
      Add an expiration date to short URLs, after which they will no longer work.

### Additional Features to Explore (To-Do)
- [ ] **Custom URL Aliases**  
      Allow users to specify custom aliases for their short URLs (e.g., `shortn.io/custom-alias`).

- [ ] **API Support**  
      Expose an API for developers to programmatically shorten URLs and retrieve analytics.

- [ ] **User Authentication**  
      Enable users to create accounts and manage their URLs.


- [ ] **Dark/Light Theme for QR Codes**  
      Customize the QR code colors to fit user branding or preferences.

- [ ] **Bulk URL Shortening**  
      Allow users to shorten multiple URLs at once via file upload or API.

- [ ] **Custom Expiry Times**  
      Provide more flexible options for setting expiration times (e.g., hours, days, weeks).

---
- [ ] **Malware/Phishing Detection**  
      Scan and warn users if the original URL points to potentially harmful content.

- [ ] **Preview Page for Links**  
      Show a preview page (with metadata like title, description, and image) before redirecting to the original URL.

- [ ] **Analytics Dashboard**  
      Provide a user-friendly dashboard to view detailed statistics (e.g., geolocation, browser, platform) for each URL.


## Development Goals
This project aims to improve understanding of:
- The Rust programming language
- Web application development using `actix-web`
- Backend architecture design
- Implementing security and scalability in web services

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/shortn.git
   cd shortn
   ```
2. Install dependencies:
   Ensure you have Rust installed. Then run:
   ```bash
   cargo build
   ```
3. Start the development server:
   ```bash
   cargo run
   ```

4. Access the application at `http://localhost:8080`.

## Contributing
This project is a personal learning journey, but feel free to fork and contribute! Any tips or constructive feedback are welcome.

## License
This project is licensed under the MIT License. See the LICENSE file for details.
```

Dengan format ini, GitHub akan menampilkan checklist sebagai kotak interaktif yang dapat Anda centang atau kosongkan secara langsung di tampilan web. Jika checklist masih tidak muncul dengan benar, pastikan bahwa file memiliki ekstensi `.md` dan sudah di-*push* ke repository GitHub Anda. 😊