# Artrise

Artrise is a web platform for artists to showcase and sell their artwork. It allows users to upload their image/video arts in the fields of drawing, song, film direction, and sculpture. The uploaded artworks go through a verification process by critics, and if approved, they are made available in the feeds of all users. Additionally, users can also sell their art through the platform.

## Features

- User registration and authentication
- Upload and management of image/video artworks
- Artwork verification process by critics
- Artwork feeds for all users
- Artwork sales functionality

## Technologies Used

- Frontend: HTML, CSS, JavaScript (AJAX)
- Backend: PHP
- Database: MySQL
- Authentication: PHP inbuilt finctions
- Email: PHPMailer (for sending account-related emails)

## Installation

To run the Artrise application locally, follow these steps:

1. Download XAMPP:
   - Visit the official XAMPP website at https://www.apachefriends.org/.
   - Download the appropriate XAMPP version for your operating system (Windows, macOS, or Linux).

2. Run the Installer:
   - Double-click the downloaded XAMPP installer file to start the installation process.
   - Follow the on-screen instructions to proceed with the installation.
   - Choose the components you want to install (Apache, MySQL, PHP, phpMyAdmin, etc.).
   - Select the installation directory (default is recommended).
   - Complete the installation process.

3. Start XAMPP:
   - After the installation is complete, locate and launch the XAMPP Control Panel.
   - Start the Apache and MySQL modules by clicking the "Start" button next to each module.
   - Wait for the modules to start (the corresponding "Running" message should appear).

4. Test XAMPP:
   - Open a web browser (e.g., Chrome, Firefox).
   - Type `http://localhost` or `http://127.0.0.1` in the address bar and press Enter.
   - If XAMPP is running correctly, the XAMPP welcome page should appear.

5. Configure PHP and MySQL:
   - To configure PHP settings, locate the `php.ini` file in the XAMPP installation directory (e.g., `C:\xampp\php\php.ini`).
   - Open the `php.ini` file with a text editor and make necessary modifications (e.g., adjusting memory_limit, upload_max_filesize).
   - To configure MySQL, access the phpMyAdmin interface by visiting `http://localhost/phpmyadmin` in your web browser.
   - Create a new database for Artrise (e.g., "artrise_db") using the phpMyAdmin interface.
   - Import the provided database

6. Move Artrise Files:
   - Clone or download the Artrise project files from the repository.
   - Move the project files to the XAMPP htdocs directory. For example, in Windows, it is typically located at `C:\xampp\htdocs\artrise`.

7. Access Artrise:
   - In your web browser, visit `http://localhost/artrise` (assuming "artrise" is the project folder name).
   - The Artrise application should now be accessible, and you can proceed with the installation and setup specific to your project.

Make sure to adjust the installation and configuration steps based on your operating system and specific requirements. XAMPP provides a convenient local development environment for running PHP applications like Artrise on your own machine.

- Alternatively, you can access the live version of Artrise at http://artrise.byethost13.com.

## Contributing
If you would like to contribute to Artrise, follow these steps:

- Fork the repository.
- Create a new branch for your feature/bug fix.
- Make your changes and commit them.
- Push your changes to your forked repository.
- Submit a pull request to the main repository.
- Please ensure your code follows the established coding style and includes relevant tests.

## Images

![Screenshot 2023-07-12 215228](https://github.com/Ritesh-K-G/ArtRise/assets/96720123/f092dc3f-06c2-4cb0-a934-5096be8e4b16)
![Screenshot 2023-07-12 215305](https://github.com/Ritesh-K-G/ArtRise/assets/96720123/24c26361-8860-4d9c-959b-80af1a941eb6)
![Screenshot 2023-07-12 215413](https://github.com/Ritesh-K-G/ArtRise/assets/96720123/1576b121-3c5c-403c-ab51-4862f8272fbd)
![Screenshot 2023-07-12 215336](https://github.com/Ritesh-K-G/ArtRise/assets/96720123/c4bf0185-f63a-4700-a780-d0b512a8679e)
![Screenshot 2023-07-12 215413](https://github.com/Ritesh-K-G/ArtRise/assets/96720123/eb078b62-bec9-46f5-8424-b0a0db5ddfe4)


## ER Diagram
![ArtRise_ERD](https://github.com/user-attachments/assets/981b18c8-40a2-4047-b59f-4d77dee6e0c9)

## Schema Of Project
![ArtRise_Schema](https://github.com/user-attachments/assets/7e140bd5-cfd3-472a-98b5-c3554569c5e6)

