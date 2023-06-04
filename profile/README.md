<h1 align="center"> BOOKSHELF </h1>


<p align="center">
  <img src="https://raw.githubusercontent.com/ohara-bookshelf/.github/22123fc824285cd136218c35a0853ccb20331aa3/images/ohara-logo-non-bg.png" width="300" height="300"/>
</p>

Table of content

* [Overview](#overview)
* [Features](#features)
  * [Authentication & Authorization](#authentication-authorization)
  * [Dashboard](#dashboard)
    * [Popular Bookshelves](#popular-books)
    * [Recommended Books](#recommended-books)
    * [Recommended Bookshelves](#recommended-bookshelves)
  * [User Profile](*user-profile)
    * [Bookshelves](#bookshelves)
      * [Create Bookshelf](#create-bookshelf)
      * [Add Books to a Given Bookshlef](#add-books-to-a-given-bookshelf)
      * [View Book](#view-book)
    * [Fork or Unfork Bookshelf](#fork-or-unfork-bookshelf)
    
* [Used Technologies](#used-technologies)
  * [Tech Stack](#tech-stack)
    * [Backend](#backend)
    * [Frontend](#frontend)
  * [Recommendation Systems(Machine learning)](#machine-learning)
    * [Popularity-Based Filtering Recommendation](#popularity-based-filtering-recommendation)
    * [Content-Based Filtering Recommendation](#content-based-filtering-recommendation)
    * [Collaborative Filtering Recommendation](#collaborative-filtering-recommendation)
    * [Hybrid-Based Filtering Recommendation](#hybrid-based-filtering-recommendation)
    
    


## Overview:

  Bookshelf is a open source organization where my friend and I collaborated to developed our final year project on the computer engineering major.

  The organization is basically a software developed, to exhale and faciliate the bibliomaniacs reading routine. 
  Bookshelf is a fully function website where readers can signup/signin, add new a want-to-read bookshelves, also fork/unfork other bibliomaniacs bookshelves. 
  According to the bookshelves collected by a user, a machine learning algorithm will generate a books recommendation which covers their interest.

## Features:
### Authentication & Authorization
  We've used google authentication/authorization to make authentication/authorization safer and easier.
  
   <table align="center">
     <tr>
        <td>
          <p align="center">
            <img src="https://github.com/Tasarim-Bitirme/.github/blob/main/images/login.png?raw=true"/>
          </p>
        </td>
        <td>
          <p align="center">
            <img src="https://github.com/Tasarim-Bitirme/.github/blob/main/images/login3.png?raw=true"/>
          </p>
        </td>
      </tr>
  </table>


### Dashboard
  The dashboard contains the following 3 sections:
  
  #### Popular Bookshelves:
  Here we've used the popularity based recommendation algorithm and most forked books feature to display popular bookshelves.
  
  <p align="center">
    <img src="https://github.com/Tasarim-Bitirme/.github/blob/main/images/home-page-popular-books.png?raw=true" width="700" height="300"/>
  </p>
  
  #### Recommended Books
  Using the hybrid based recommendation algorithm(discribed later), a set of books will be displayed on this section.
    <p align="center">
      <img src="https://github.com/Tasarim-Bitirme/.github/blob/main/images/home-recommendation.png?raw=true" width="700" height="300"/>
    </p>
  #### Recommended Bookshelves
   Recommending bookshelves is done according to the current user's owned bookshelves.
  <p align="center">
    <img src="https://github.com/Tasarim-Bitirme/.github/blob/main/images/home-recommended-bookshelves.png?raw=true" width="700" height="300"/>
  </p>
  
### User Profile:
  #### Bookshelves:
<p align="center">
  <img src="https://github.com/Tasarim-Bitirme/.github/blob/main/images/home-profile-bookshelves-visibility.png?raw=true" width="700" height="300"/>
</p>


#### Create Bookshelf

<p align="center">
  <img src="https://github.com/Tasarim-Bitirme/.github/blob/main/images/create-bookshelf.png?raw=true" width="700" height="300"/>
</p> 

  #### Add Books to a Given Bookshlef
<p align="center">
  <img src="https://github.com/Tasarim-Bitirme/.github/blob/main/images/add-books.png?raw=true" width="700" height="300"/>
</p>

  #### View Bookshelf:
<p align="center">
  <img src="https://github.com/Tasarim-Bitirme/.github/blob/main/images/change-visubility-delelte-bookshelf-delete-book.png?raw=true" width="700" height="300"/>
</p>
### Fork or Unfork Bookshelf:
  This feature can be performed in all bookshelves created publicly. 
  Each user will have the full control on forked bookshelves.
  The inspiration of this feature comes from the github's forking 
  
## Used Technologies:
  The development of this software has evolved multiple technologies highly used on the software development industry. 
  As it is a full stack project powered with machine learning algorithms, it has allowed us to acquire the required knowledge to become full-stack web developers.

### Tech Stack:

#### Backend:

- [nestjs](https://nestjs.com/)
- [postgres](https://postgresql.org/)
- [prisma](https://prisma.io/)
- [class-transformer](https://github.com/typestack/class-transformer)
- [class-validator](https://github.com/typestack/class-validator)
- [google oauth](https://developers.google.com/identity/protocols/oauth2)
- [passport](https://passportjs.org/)
- [morgan](https://github.com/expressjs/morgan/)
- [passport](https://passportjs.org/)
- [passport](https://passportjs.org/)

#### Frontend:

- [react](https://reactjs.org/)
- [tanstack query](https://tanstack.com/query/v4)
- [react router dom](https://reactrouter.com/en/main)
- [chakra ui](https://chakra-ui.com/)
- [formik](https://formik.org/)
- [yup](https://github.com/jquense/yup)
- [axios](https://axios-http.com/)
- [vite](https://vitejs.dev/)
- [react oauth](https://github.com/MomenSherif/react-oauth)
- [framer motion](https://framer.com/)
- [react icon](https://react-icons.github.io/react-icons/)

#### DevTools:

* [git](https://git-scm.com/)
* [github](https://github.com/)
* [docker](https://docker.com/)
* [render](https://render.com/)
* [postman](https://postman.com/)
* [prettier](https://prettier.io/)
* [eslint](https://eslint.org/)
* [husky](https://typicode.github.io/husky/)


#### Recommendation Systems(Machine Learning):

<p align="center">
  <img src="https://github.com/Tasarim-Bitirme/.github/blob/main/images/recommendation-system.png?raw=true" width="700" height="300"/>
</p>

  A recommendation system is usually built using 3 techniques which are content-based filtering, collaborative filtering, 
  and a combination of both. Other then those 3 techniques there is another popular, simple and widely used recommendation 
  technique which is popularity-based filtering.
  
  In the project, The implementation of these algorithms is done in python jupyter IDE. 
  


##### Popularity-Based Filtering Recommendation:

<p align="center">
  <img src="https://github.com/Tasarim-Bitirme/.github/blob/main/images/popularity-based-recommendation.png?raw=true" width="700" height="300"/>
</p>

It is a type of recommendation system which works on the principle of popularity and or anything which is in trend. 
These systems check about the product which are in trend or are most popular among the users and directly recommend them to the users. 


  
##### Content-Based Filtering Recommendation:

<p align="center">
  <img src="https://github.com/Tasarim-Bitirme/.github/blob/main/images/content%20based.png?raw=true"/>
</p>
The algorithm recommends similar products consumed by the user. In simple words, In this algorithm, we try to find  item look alike. In a nutshell, let’s say a person X has read ‘Harry potter and the prisoner of Azkaban’, the algorithm will recommend them the other books on the Harry potter Saga.
Only it looks similar between the content and does not focus more on the person who is watching this. 
Only it recommends the product which has the highest score based on past preferences.

##### Collaborative Filtering Recommendation:

<p align="center">
  <img src="https://github.com/Tasarim-Bitirme/.github/blob/main/images/collaborative%20filtering.png?raw=true"/>
</p>

Collaborative based filtering recommendation systems are based on past interactions of users and target items.  
In simple words here, we try to search for the look-alike customers and offer products based on what his or her lookalike has chosen. 
Let us understand with an example. X and Y are two similar users and X user has watched A, B, and C movie. 
And Y user has watched B, C, and D movie then we will recommend A movie to Y user and D movie to X user.
YouTube has shifted its recommendation system from content-based to Collaborative based filtering technique. 
If you have experienced sometimes there are also videos which not at all related to your history but then also 
it recommends it because the other person similar to you has watched it.

##### Hybrid-Based Filtering Recommendation:

<p align="center">
  <img src="https://github.com/Tasarim-Bitirme/.github/blob/main/images/hybrid-based-recommendation.png?raw=true" width="700" height="300"/>
</p>
    
It is basically a combination of both the above methods. It is a too complex model which recommends product based 
on your history as well based on similar users like you.
There are some organizations that use this method like Facebook which shows news which is important for you and for 
others also in your network and the same is used by LinkedIn too.



## References:
### Recommendation Images:
https://towardsdatascience.com/brief-on-recommender-systems-b86a1068a4dd
https://www.researchgate.net/figure/The-Schema-for-the-model-based-popularity-mitigation_fig12_343768911
https://medium.com/double-pointer/system-design-interview-recommendation-system-design-as-used-by-youtube-netflix-etc-c457aaec3ab

### Recommendation Algorithms:
https://www.analyticsvidhya.com/blog/2021/06/build-book-recommendation-system-unsupervised-learning-project/
https://analyticsindiamag.com/a-guide-to-building-hybrid-recommendation-systems-for-beginners/


## Contributors

<div align="center">
<table>
  <tr>
<td align="center">
<a href="https://github.com/zidanomar">
<img src="https://avatars.githubusercontent.com/u/57989473?v=4" width="100px;" alt="" style="border-radius:50%"/>
<br />
<sub><b>Zidan Omar Hamid</b></sub>
</a>
<br />
</td>
<td align="center">
<a href="https://github.com/dembasow98">
<img src="https://avatars.githubusercontent.com/u/62963091?v=4" width="100px;" alt="Demba Sow" style="border-radius:50%"/>
<br />
<sub><b>Demba Sow</b></sub>
</a>
<br />
</td>
  
</tr>
</table>
</div>




## License

[![MIT License][license-shield]][license-url]<br>
Distributed under the MIT License. See `LICENSE` for more information.



[license-shield]: https://img.shields.io/github/license/othneildrew/Best-README-Template.svg?style=for-the-badge
[license-url]: https://github.com/Tasarim-Bitirme/.github/blob/main/LICENCE.md
