<h1 align="center">
  <picture>
    <source
      srcset="./screenshots/fenestrax_logo_light.png"
      media="(prefers-color-scheme: light)"
    />
    <source
      srcset="./screenshots/fenestrax_logo.png"
      media="(prefers-color-scheme: dark)"
    />
    <img
      src="./screenshots/fenestrax_logo.png"
      alt="Fenestrax Logo"
      width="200"
    />
  </picture>
</h1>

![Login Page](./screenshots/login_page.png)

## Description

- **Surgical planning platform** for designing customized grafts used to **treat aortic aneurysms**, helping surgeons plan complex procedures for a disease responsible for **more than 150,000 deaths worldwide each year**.

- **Reduces preoperative planning time by over 80%** by using AI and geometric analysis techniques.

- **Includes interactive editing tools** that enable surgeons to refine and validate the automated measurements, **ensuring clinically accurate treatment plan**.

## Supervision

<table>
<tr>
<td width="80%">

This plaltform was developed under the supervision of **Astute Imaging**, whose team **provided continuous technical guidance and clinical feedback** throughout the development process.

</td>
<td align="center" width="20%">
<img src="./screenshots/astute_imaging_logo.png" alt="Astute Imaging" width="140"/>
</td>
</tr>
</table>

## Tech Stack Used

| **Frontend**   | [![React](https://img.shields.io/badge/React-%2320232a.svg?logo=react&logoColor=%2361DAFB)](#) [![Next.js](https://img.shields.io/badge/Next.js-black?logo=next.js&logoColor=white)](#) [![Cornerstone3D](./screenshots/Cornerstone3D_badge.svg)](#) [![Three.js](https://img.shields.io/badge/Three.js-000?logo=threedotjs&logoColor=fff)](#) |
| -------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Styling**    | [![TailwindCSS](https://img.shields.io/badge/Tailwind%20CSS-%2338B2AC.svg?logo=tailwind-css&logoColor=white)](#) [![FontAwesome](./screenshots/FontAwesome_badge.svg)](#)                                                                                                                                                                      |
| **Backend**    | [![Flask](https://img.shields.io/badge/Flask-000?logo=flask&logoColor=fff)](#)                                                                                                                                                                                                                                                                 |
| **AI Model**   | [![PyTorch](https://img.shields.io/badge/PyTorch-ee4c2c?logo=pytorch&logoColor=white)](#)                                                                                                                                                                                                                                                      |
| **Database**   | [![Postgres](https://img.shields.io/badge/Postgres-%23316192.svg?logo=postgresql&logoColor=white)](#) [![Prisma](https://img.shields.io/badge/Prisma-2D3748?logo=prisma&logoColor=white)](#)                                                                                                                                                   |
| **Deployment** | [![Google Cloud](https://img.shields.io/badge/Google%20Cloud-%234285F4.svg?logo=google-cloud&logoColor=white)](#) [![Supabase](https://img.shields.io/badge/Supabase-3FCF8E?logo=supabase&logoColor=fff)](#)                                                                                                                                   |

## Features

- **Multi-Planar Reconstruction** of CT scan in 2D & 3D views

- **Flexible Input Parsing** of different formats **(DICOM, NRRD, NIFTI)**

![Multi-Planar Reconstruction](./screenshots/multi_planar_reconstruction.png)

- **Measurement & Annotation Tools** for 2D views

![Measurement & Annotation Tools](./screenshots/twoD_annotation.gif)

- **Interactive 2D Manipulation** including zooming, panning, rotating, and **synchronized brightness and contrast manipulation**

![2D Manipulation](./screenshots/twoD_manipulation.gif)

- **Interactive 3D Manipulation** including changing the opacity for better visualization of the arteries

![3D Manipulation](./screenshots/threeD_interaction.gif)

- **Automatic Segmentation** of aorta and arteries with **Dice Score 0.88** utilizing a deep learning model **trained on 52,000 axial slices**

![Segmentation of Aorta and Arteries](./screenshots/segmentation_view.png)

- **Segmentation Editing** for surgeons to manually verify the aorta and arteries regions

![Segmentation Edit](./screenshots/segmentation_edit.gif)

- **Automatic Centerline Extraction & Labelling** which allows automatic localization of branching arteries openings

![Centerline Extraction](./screenshots/centerline_extraction_filtering.gif)

- **Centerline Editing** for surgeons to manually verify the center points of the aorta and arteries

![Centerline Editing](./screenshots/centerline_edit.gif)

- **Surgical Planning Report Generation** as an exportable **PDF report** containing the automated measurements and surgeon modifications, enabling **easy sharing and documentation** of the final surgical plan.

![Report](./screenshots/report.png)

## Acknowledgement

We would like to express our sincere gratitude to our project supervisors:

| Name                         | Position                                                                                               | LinkedIn                                                                                                                                                              |
| ---------------------------- | ------------------------------------------------------------------------------------------------------ | --------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Prof. Ahmed Ehab Mahmoud** | COO & Co-Founder, Astute Imaging<br>Faculty Member, Systems & Biomedical Engineering, Cairo University | [![LinkedIn](https://custom-icon-badges.demolab.com/badge/LinkedIn-0A66C2?logo=linkedin-white&logoColor=fff)](https://www.linkedin.com/in/ahmedmahmoud)               |
| **Dr. Manar Nasser**         | Product Manager, Astute Imaging                                                                        | [![LinkedIn](https://custom-icon-badges.demolab.com/badge/LinkedIn-0A66C2?logo=linkedin-white&logoColor=fff)](https://www.linkedin.com/in/manar-nasser-ph-d-15676361) |

Their invaluable guidance, continuous support, insightful feedback, and encouragement throughout this project have been instrumental in its success. We deeply appreciate the time, expertise, and dedication they devoted to helping us achieve our goals.

## Team Members

| Name              | GitHub                                                                                                                           | LinkedIn                                                                                                                                                                |
| ----------------- | -------------------------------------------------------------------------------------------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Mostafa Ayman     | [![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?logo=github&logoColor=white)](https://github.com/mostafa-aboelmagd) | [![LinkedIn](https://custom-icon-badges.demolab.com/badge/LinkedIn-0A66C2?logo=linkedin-white&logoColor=fff)](https://www.linkedin.com/in/mostafa--aboelmagd/)          |
| Louai Khaled      | [![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?logo=github&logoColor=white)](https://github.com/louai111)          | [![LinkedIn](https://custom-icon-badges.demolab.com/badge/LinkedIn-0A66C2?logo=linkedin-white&logoColor=fff)](https://linkedin.com/in/louai-eleslamboly1/)              |
| Ali Younis        | [![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?logo=github&logoColor=white)](https://github.com/aliyounis33)       | [![LinkedIn](https://custom-icon-badges.demolab.com/badge/LinkedIn-0A66C2?logo=linkedin-white&logoColor=fff)](https://www.linkedin.com/in/ali-younis-98b780277/)        |
| Zeyad Amr         | [![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?logo=github&logoColor=white)](https://github.com/zeyad-amr-22)      | [![LinkedIn](https://custom-icon-badges.demolab.com/badge/LinkedIn-0A66C2?logo=linkedin-white&logoColor=fff)](https://www.linkedin.com/in/zeyad-amr-3506b225b/)         |
| Abdelrahman Sayed | [![GitHub](https://img.shields.io/badge/GitHub-%23121011.svg?logo=github&logoColor=white)](https://github.com/Abdelrahman0Sayed) | [![LinkedIn](https://custom-icon-badges.demolab.com/badge/LinkedIn-0A66C2?logo=linkedin-white&logoColor=fff)](https://www.linkedin.com/in/abdelrahman-sayed-94aa62248/) |
