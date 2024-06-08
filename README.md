# Wanderlust

Wanderlust is a property rental website inspired by Airbnb. It allows property owners to list their properties with photos and details, and enables viewers to view property locations on an interactive map, leave reviews, and rate properties out of 5 stars. The project leverages several modern technologies to provide a seamless and secure user experience.

## Features

- Property owners can list their properties with detailed descriptions and photos.
- Viewers can browse properties, view their locations on an interactive map, leave reviews, and rate properties.
- Integrated Mapbox API for precise map views of property locations.
- Secure user authentication using Passport-OAuth middleware.
- Responsive design using Bootstrap for cross-device compatibility.

## Technologies Used

- **Backend:** Express.js, Node.js
- **Frontend:** JavaScript, Bootstrap
- **Database:** MongoDB
- **APIs:** Mapbox API
- **Authentication:** Passport-OAuth

## Getting Started

### Prerequisites

- Node.js
- MongoDB
- Mapbox API Key
- Passport-OAuth Client ID and Secret

### Installation

1. **Clone the repository:**

    ```bash
    git clone https://github.com/sagarmaiti26/wanderlust.git
    cd wanderlust
    ```

2. **Install dependencies:**

    ```bash
    npm install
    ```

3. **Create a `.env` file in the root directory and add your environment variables:**

    ```env
    PORT=8080
    MONGODB_URI=your_mongodb_connection_string
    MAPBOX_API_KEY=your_mapbox_api_key
    PASSPORT_OAUTH_CLIENT_ID=your_passport_oauth_client_id
    PASSPORT_OAUTH_CLIENT_SECRET=your_passport_oauth_client_secret
    ```

4. **Start the server:**

    ```bash
    npm start
    ```

### Usage

- **Home Page:** View a list of all available properties.
- **Property Detail Page:** View detailed information about a property, including photos, descriptions, reviews, and ratings.
- **Map View:** See the precise location of properties on an interactive map.
- **User Authentication:** Log in or sign up using secure OAuth authentication.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes. Ensure that your code follows the existing style guidelines and includes appropriate tests.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or feedback, feel free to reach out:

- **Email:** your.email@example.com
- **GitHub:** [sagarmaiti26](https://github.com/sagarmaiti26)

---

Thank you for using Wanderlust! We hope you enjoy your property rental experience.