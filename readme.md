# Blazor Portfolio

Live Demo : https://itsmefais.azurewebsites.net/

This repository contains a personal portfolio website built using [Blazor WebAssembly](https://dotnet.microsoft.com/en-us/apps/aspnet/web-apps/blazor) and styled with [Tailwind CSS](https://tailwindcss.com/). The site showcases projects and skills, providing an interactive platform to present professional information.

## Features

- **Single-Page Application (SPA):** Utilizes Blazor WebAssembly for a seamless user experience.
- **Responsive Design:** Ensures optimal viewing across various devices.
- **Project Showcase:** Displays detailed information about personal projects.
- **Contact Form:** Allows visitors to get in touch directly through the site.

## Prerequisites

- [.NET SDK](https://dotnet.microsoft.com/download) (version 8.0 or later)
- [Node.js](https://nodejs.org/) (for managing frontend dependencies)

## Getting Started

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/faisalk1666/blazor-portfolio.git
   cd blazor-portfolio
   ```

2. **Install Frontend Dependencies:**

   ```bash
   npm install
   ```

3. **Build the Project:**

   ```bash
   dotnet build
   ```

4. **Run the Application:**

   ```bash
   dotnet run
   ```

   Navigate to `https://localhost:5001` in your browser to view the site.

## Project Structure

- `Components/`: Contains reusable Blazor components.
- `wwwroot/`: Static assets such as images and CSS files.
- `Program.cs`: Entry point of the application.
- `projectsbyfais.csproj`: Project file defining dependencies and build configurations.

## Customization

- **Tailwind CSS Configuration:** Modify `tailwind.config.js` to customize the design.
- **Content Updates:** Update the content directly within the Blazor components located in the `Components/` directory.

## Deployment

To deploy the application:

1. **Publish the Application:**

   ```bash
   dotnet publish --configuration Release
   ```

2. **Deploy to a Web Server:**

   - Copy the contents of the `bin/Release/net8.0/publish/wwwroot` directory to your web server.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the [Apache License Version 2.0](http://www.apache.org/licenses/LICENSE-2.0).

## Acknowledgements

- [Blazor WebAssembly](https://dotnet.microsoft.com/en-us/apps/aspnet/web-apps/blazor)
- [Tailwind CSS](https://tailwindcss.com/)

For any questions or suggestions, please open an issue in this repository.