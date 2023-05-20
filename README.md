<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>
<!--
*** Thanks for checking out the Best-README-Template. If you have a suggestion
*** that would make this better, please fork the repo and create a pull request
*** or simply open an issue with the tag "enhancement".
*** Don't forget to give the project a star!
*** Thanks again! Now go create something AMAZING! :D
-->



<!-- PROJECT SHIELDS -->
<!--
*** I'm using markdown "reference style" links for readability.
*** Reference links are enclosed in brackets [ ] instead of parentheses ( ).
*** See the bottom of this document for the declaration of the reference variables
*** for contributors-url, forks-url, etc. This is an optional, concise syntax you may use.
*** https://www.markdownguide.org/basic-syntax/#reference-style-links
-->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]



<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/github_username/repo_name">
    <img src="images/logo.png" alt="Logo" width="80" height="80">
  </a>

<h3 align="center">Referral Request</h3>

  <p align="center">
    Project_description
    <br />
    <a href=#><strong>Explore the docs »</strong></a>
    <br />
  </p>
</div>



<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
        <li><a href="#installation">Installation</a></li>
        <li><a href="#set-up">Set-up</a></li>
      </ul>
    </li>
    <li><a href="#usage">Usage</a></li>
    <li><a href="#roadmap">Roadmap</a></li>
    <li><a href="#contributing">Contributing</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project

[![Product Name Screen Shot][product-screenshot]]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With
* [![Laravel][Laravel.com]][Laravel-url]
* [![Bootstrap][Bootstrap.com]][Bootstrap-url]

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

### Prerequisites

* npm
  ```sh
  npm install npm@latest -g
  ```

### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/github_username/repo_name.git
   ```
2. Install dependencies - missing `composer packages`
   ```sh
   composer install
   ```  
3. Install NPM packages
   ```sh
   npm install
   ```
4. Create a .env file
   ```sh
   -> Copy content from .env.example
   -> Paste it in your .env file
5. Run php `artisan key:generate`

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Set-up

1. Setup Database Credentials in the .env file.
   ```sh
   DB_HOST=localhost
   DB_DATABASE=''
   DB_USERNAME=''
   DB_PASSWORD=''
   ```
2. Publish all the schema to the database.
   ```sh
   php artisan:migrate
   ```  
3. Seed the database with dummy users.
   ```sh
   php artisan tinker
   User::factory()->count(5)->create()
   ```
4. Navigate to your browser and type in “localhost/foldernameinHTdocs/” in the address bar to access the login page.
5. How to get the users' credentials
   ```sh
   -> Access your database
   -> Open the users table
   -> Copy any of the usernames and paste it in the login page - username section
   -> The password is, "password"
6. Create faker for user and roles
   ```sh
   -> Edit the roles table.
   -> Insert the role, guard_name, and the logged in user id in the role_id

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

* []()
* []()
* []()

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

* []()
* []()
* []()

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/TUM-HIS/Referral-Request-FrontEnd.svg?style=for-the-badge
[contributors-url]: https://github.com/TUM-HIS/Referral-Request-FrontEnd.git/contributors

[forks-shield]: https://img.shields.io/github/forks/TUM-HIS/Referral-Request-FrontEnd.svg?style=for-the-badge
[forks-url]: https://github.com/TUM-HIS/Referral-Request-FrontEnd.git/network/members

[stars-shield]: https://img.shields.io/github/stars/TUM-HIS/Referral-Request-FrontEnd.svg?style=for-the-badge
[stars-url]: https://github.com/TUM-HIS/Referral-Request-FrontEnd.git/stargazers

[issues-shield]: https://img.shields.io/github/issues/TUM-HIS/Referral-Request-FrontEnd.svg?style=for-the-badge
[issues-url]: https://github.com/TUM-HIS/Referral-Request-FrontEnd-Template/issues

[product-screenshot]: images/screenshot.png

[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com

[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
