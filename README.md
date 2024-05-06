<div id="top"></div>

<!-- PROJECT SHIELDS -->
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="[https://github.com/linitio/openstack-freebsd-image](https://github.com/linitio/openstack-freebsd-image)">
    <img src="images/logo.svg" alt="Logo" width="250">
  </a>

<h3 align="center">FreeBSD image for OpenStack</h3>

  <p align="center">
    Simple port of FreeBSD distribution for OpenStack environments
    <br />
    <a href="https://github.com/linitio/openstack-freebsd-image"><strong>Explore the docs »</strong></a>
    <br />
    <br />
    <a href="https://github.com/linitio/openstack-freebsd-image/issues">Report Bug</a>
    ·
    <a href="https://github.com/linitio/openstack-freebsd-image/issues">Request Feature</a>
  </p>
</div>

<!-- ABOUT THE PROJECT -->
## About The Project

This project is a simple port of FreeBSD releases for OpenStack environments.  
This image used the the project [Build Cloud image for FreeBSD](https://github.com/virt-lightning/freebsd-cloud-images "Build Cloud image for FreeBSD") to build base image and we make some change to make it compatible with OpenStack environments and cloud-init.  

This image is updated when Alpine Linux team released a new version of the OS [here](https://www.freebsd.org/releases/ "FreeBSD Release Inventory").


<p align="right">(<a href="#top">back to top</a>)</p>

### How to use this image

1. Set your OpenStack environement variables
2. Download the latest image from the [repository page](https://s3.openimages.cloud/freebsd-image/index.html# "Repository page")
3. Upload image to your OpenStack environment
   ```sh
   openstack image create --disk-format=qcow2 --container-format=bare --file freebsd-<VERSION>-amd64.qcow2  'FreeBSD <VERSION>'
   ```

<p align="right">(<a href="#top">back to top</a>)</p>

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

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- LICENSE -->
## License

Distributed under the GPL-3.0 License. See `LICENSE.md` for more information.

<p align="right">(<a href="#top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

Kevin Allioli - [@linit_io](https://twitter.com/linit_io) - kevin@linit.io

Project Link: [https://github.com/linitio/openstack-freebsd-image](https://github.com/linitio/openstack-freebsd-image)

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/linitio/openstack-freebsd-image.svg?style=for-the-badge
[contributors-url]: https://github.com/linitio/openstack-freebsd-image/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/linitio/openstack-freebsd-image.svg?style=for-the-badge
[forks-url]: https://github.com/linitio/openstack-freebsd-image/network/members
[stars-shield]: https://img.shields.io/github/stars/linitio/openstack-freebsd-image.svg?style=for-the-badge
[stars-url]: https://github.com/linitio/openstack-freebsd-image/stargazers
[issues-shield]: https://img.shields.io/github/issues/linitio/openstack-freebsd-image.svg?style=for-the-badge
[issues-url]: https://github.com/linitio/openstack-freebsd-image/issues
[license-shield]: https://img.shields.io/github/license/linitio/openstack-freebsd-image.svg?style=for-the-badge
[license-url]: https://github.com/linitio/openstack-freebsd-image/blob/master/LICENSE.md
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/kevinallioli
