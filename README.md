# Data_Professionals

<!-- Improved compatibility of back to top link: See: https://github.com/othneildrew/Best-README-Template/pull/73 -->
<a name="readme-top"></a>

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
[![MIT License][license-shield]][license-url]
[![LinkedIn][linkedin-shield]][linkedin-url]


<!-- PROJECT LOGO -->
<br />
<div align="center">
  <a href="https://github.com/ishamahadalkar/Data_Professionals">
    <img src="logo.JPG" alt="Logo" >
  </a>
  
<!-- Section Name tag -->
<a name="#about-the-project"></a>
<h3 align="center">Empowering Data Excellence with Power BI</h3>

  <p align="center">
    This project aims to analyze survey data from data professionals using Power BI for data cleaning and dashboard creation. The objective is to extract insights from the survey data and visualize key trends and patterns using dashboards.
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
      </ul>
    </li>
    <li><a href="#data-sources">Data Sources</a>
      <ul>
          <li><a href="#preprocessing">Preprocessing</a></li>
      </ul>
    </li>
    <li><a href="#approach">Approach</a></li>
    <li><a href="#code-structure">Code Structure</a></li>
    <li><a href="#lessons-learned">Lessons Learned</a></li>
    <li><a href="#future-work">Future Work</a></li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
    <li><a href="#acknowledgments">Acknowledgments</a></li>
  </ol>
</details>

<!-- Section Name tag -->
<a name="#built-with"></a>

### Built With

* [![Power BI][powerbi-shield]][powerbi-url]
* [![DAX][dax-shield]][dax-url]
  
<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- GETTING STARTED -->
## Getting Started

<!-- Section Name tag -->
<a name="#getting-started"></a>

### Prerequisites

<!-- Section Name tag -->
<a name="#prerequisites"></a>

- Environment Setup: Install Power BI Desktop to begin working with the data. Visit the official Power BI website and download the desktop version.
- Basic Data Analysis Knowledge: Familiarity with data cleaning and visualization concepts.

### Installation

<!-- Section Name tag -->
<a name="#installation"></a>

1. Clone the repo
   ```sh
   git clone https://github.com/ishamahadalkar/Data_Professionals
   ```
2. Download the survey data file from the provided link.
<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- DATA SOURCES -->
## Data Sources

<!-- Section Name tag -->
<a name="#data-sources"></a>

Survey Data: The dataset consists of responses from data professionals regarding various aspects of their roles, skills, and experiences.

### Preprocessing

<!-- Section Name tag -->
<a name="#preprocessing"></a>

- Deleting Unused Columns: Remove columns not relevant to the analysis.
- Cleaning Text Columns: Standardize text values (e.g., replacing "Other" with a consistent label).
- Splitting Columns: Separate combined data into individual attributes using delimiters.
- Calculating Average Salary: Use DAX to calculate average salary from salary range data.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- APPROACH -->
## Approach

<!-- Section Name tag -->
<a name="#approach"></a>

1. Data Cleaning: Utilize Power BI's data cleaning features to prepare the dataset for analysis.
2. Dashboard Creation: Design interactive dashboards to visualize survey insights.
3. Color Blind Friendly Theme: Implement a color scheme that is accessible to color-blind individuals for enhanced readability.


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- CODE STRUCTURE -->
## Code Structure

<!-- Section Name tag -->
<a name="#code-structure"></a>

- Data_Professional.pbix: Final PowerBI file.
- DataProfessional.xlsx: Dataset containing the data professionals survey data.
- Dashboard.pdf: Final Dashboard.


<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- Lessons Learned -->
## Lessons Learned

<!-- Section Name tag -->
<a name="#lessons-learned"></a>

1. Power BI Proficiency: Enhanced skills in using Power BI for data cleaning and visualization.
2. Data Preparation Techniques: Learned effective methods for preprocessing survey data.
3. Dashboard Design Principles: Gained insights into creating visually appealing and informative dashboards.


<p align="right">(<a href="#readme-top">back to top</a>)</p>

<!-- FUTURE WORK -->
## Future Work

<!-- Section Name tag -->
<a name="#future-work"></a>

- Advanced Analytics: Explore advanced analytics capabilities in Power BI, such as predictive modeling.
- Dynamic Dashboards: Implement dynamic filters and slicers for enhanced interactivity.
- Integration with Other Tools: Integrate Power BI with other tools for comprehensive data analysis.

<p align="right">(<a href="#readme-top">back to top</a>)</p>


<!-- LICENSE -->
## License

<!-- Section Name tag -->
<a name="#license"></a>

Distributed under the MIT License. See `LICENSE.txt` for more information.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- CONTACT -->
## Contact

<!-- Section Name tag -->
<a name="#contact"></a>

Your Name - [@LinkedIn]([linked-url]) - mahadalkar.isha@gmail.com

Project Link: [https://github.com/ishamahadalkar/Data_Professionals](https://github.com/ishamahadalkar/Data_Professionals)

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- ACKNOWLEDGMENTS -->
## Acknowledgments

<!-- Section Name tag -->
<a name="#acknowledgments"></a>

* Alex The Analyst - For the data professionals dataset
* Data Professionals: Gratitude to the data professionals who participated in the survey.
* Power BI Community: Acknowledgment of resources and support from the Power BI community.

<p align="right">(<a href="#readme-top">back to top</a>)</p>



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/ishamahadalkar/Data_Professionals.svg?style=for-the-badge
[contributors-url]: https://github.com/ishamahadalkar/Data_Professionals/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/ishamahadalkar/Data_Professionals.svg?style=for-the-badge
[forks-url]: https://github.com/ishamahadalkar/Data_Professionals/network/members
[stars-shield]: https://img.shields.io/github/stars/ishamahadalkar/Data_Professionals.svg?style=for-the-badge
[stars-url]: https://github.com/ishamahadalkar/Data_Professionals/stargazers
[issues-shield]: https://img.shields.io/github/issues/ishamahadalkar/Data_Professionals.svg?style=for-the-badge
[issues-url]: https://github.com/ishamahadalkar/Data_Professionals/issues
[license-shield]: https://img.shields.io/github/license/ishamahadalkar/Data_Professionals.svg?style=for-the-badge
[license-url]: https://github.com/ishamahadalkar/Data_Professionals/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://linkedin.com/in/isha-mahadalkar
[product-screenshot]: images/screenshot.png
[Next.js]: https://img.shields.io/badge/next.js-000000?style=for-the-badge&logo=nextdotjs&logoColor=white
[Next-url]: https://nextjs.org/
[React.js]: https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB
[React-url]: https://reactjs.org/
[Vue.js]: https://img.shields.io/badge/Vue.js-35495E?style=for-the-badge&logo=vuedotjs&logoColor=4FC08D
[Vue-url]: https://vuejs.org/
[Angular.io]: https://img.shields.io/badge/Angular-DD0031?style=for-the-badge&logo=angular&logoColor=white
[Angular-url]: https://angular.io/
[Svelte.dev]: https://img.shields.io/badge/Svelte-4A4A55?style=for-the-badge&logo=svelte&logoColor=FF3E00
[Svelte-url]: https://svelte.dev/
[Laravel.com]: https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white
[Laravel-url]: https://laravel.com
[Bootstrap.com]: https://img.shields.io/badge/Bootstrap-563D7C?style=for-the-badge&logo=bootstrap&logoColor=white
[Bootstrap-url]: https://getbootstrap.com
[JQuery.com]: https://img.shields.io/badge/jQuery-0769AD?style=for-the-badge&logo=jquery&logoColor=white
[JQuery-url]: https://jquery.com 
[MySQL.com]: https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white
[MySQL-url]: https://www.mysql.com
[MySQLWorkbench.com]: https://img.shields.io/badge/MySQL_Workbench-4479A1?style=for-the-badge&logo=mysql&logoColor=white
[MySQLWorkbench-url]: https://www.mysql.com/products/workbench/
[PowerBI-shield]: https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=white
[PowerBI-url]: https://powerbi.microsoft.com/
[DAX-shield]: https://img.shields.io/badge/DAX-00ADEF?style=for-the-badge&logo=powerbi&logoColor=white
[DAX-url]: https://docs.microsoft.com/en-us/dax/
