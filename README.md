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
[![Stargazers][stars-shield]][stars-url]
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Issues][issues-shield]][issues-url]


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/github_username/repo_name">
    <img src="https://thenounproject.com/api/private/icons/1116675/edit/?backgroundShape=SQUARE&backgroundShapeColor=%23000000&backgroundShapeOpacity=0&exportSize=752&flipX=false&flipY=false&foregroundColor=%23999999&foregroundOpacity=1&imageFormat=png&rotation=0" alt="Logo" width="128" height="128">
  </a>

<h3 align="center">CircuitCider</h3>

  <p align="center">
    A physics based robot dueler.
    <br />
    <a href="https://github.com/rydb/CircuitCider/issues">Report Bug</a>
    ·
    <a href="https://github.com/rydb/CircuitCider/issues">Request Feature</a>
  </p>
</div>




<!-- ABOUT THE PROJECT -->
## About The Project

**CircuitCider** is an open-source project focused on providing a robust simulation environment for robots. At its current stage, the program excels in loading robots from UDRF files, allowing users to explore a diverse range of robotic designs.

### Key Features
- **UDRF File Compatibility:** Seamlessly import robots using any UDRF file, ensuring flexibility in exploring various robotic models.

### Upcoming Features
- **AI Integration:** Planned future updates will introduce advanced AI functionalities, empowering users to implement intelligent behaviors and decision-making processes for their simulated robots.
- **Combat Simulation:** Experience thrilling robot battles within the program, testing different robotic creations in simulated combat scenarios.
- **In-App Robot Creation:** Unlock the ability to craft your own robots directly within the program. Customize parameters, design, and features to bring your robotic creations to life without leaving the simulation environment.

*CircuitCider* is an evolving project, and your contributions and feedback are crucial in shaping its future. Join the community, participate in development, and anticipate the exciting additions that will enhance the simulation and customization experience with *CircuitCider*.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



### Built With [![Bevy][Bevy]][Bevy-URL] [![RUST_VERSION][Rust-Version]][Rust-URL]


<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- GETTING STARTED -->
## Getting Started

### Prerequisites
* rust
```sh
  rustup update
```

### Installation

1. Create a new directory to contain the three required repositories, then move into that directory.
  ```sh
    mkdir <folder_name>
    cd <folder_name>
  ```
2. Clone the required repositories
 ```sh
   git clone https://github.com/rydb/CircuitCider.git
   git clone https://github.com/rydb/bevy_serialization_extras.git
   git clone https://github.com/rydb/bevy_serialization_urdf.git
 ```

### Build and Run

1. Navigate to your CircuitCider directory
```
  cd CircuitCider
```
2. Compile and run CurcuitCider
```
  cargo run
```
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- ROADMAP -->
## Roadmap

- [ ] A robotics combat system
  - [ ] Melee Weapons
  - [ ] Ranged Weapons
  - [ ] Health System 
- [ ] AI agents
  - [ ] AI Pathfinding
- [ ] Robot Editor
    - [ ] Prefab parts to build with
- [ ] Improved UI

See the [open issues](https://github.com/rydb/CircuitCider/issues) for a full list of proposed features (and known issues).

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

If you have a suggestion that would make this better, please fork the repo and create a pull request. You can also simply open an issue with the tag "enhancement".
Don't forget to give the project a star! Thanks again!

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- ACKNOWLEDGMENTS -->
## Acknowledgments
* [Rust](https://www.rust-lang.org/)
* [Bevy](https://bevyengine.org/)
* [Code Coogs](https://www.codecoogs.com/)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/rydb/CircuitCider.svg?style=for-the-badge
[contributors-url]: https://github.com/rydb/CircuitCider/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/rydb/CircuitCider.svg?style=for-the-badge
[forks-url]: https://github.com/rydb/CircuitCider/network/members
[stars-shield]: https://img.shields.io/github/stars/rydb/CircuitCider.svg?style=for-the-badge
[stars-url]: https://github.com/rydb/CircuitCider/stargazers
[issues-shield]: https://img.shields.io/github/issues/rydb/CircuitCider.svg?style=for-the-badge
[issues-url]: https://github.com/rydb/CircuitCider/issues
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
[Rust-Version]: https://img.shields.io/badge/Rust-1.7.2-blue?logo=rust&style=for-the-badge
[Rust-URL]: https://www.rust-lang.org/
[Bevy]: https://img.shields.io/badge/Bevy-0.12-blue?logo=bevy&style=for-the-badge
[Bevy-URL]: https://bevyengine.org/
