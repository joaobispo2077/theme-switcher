<meta charset="utf-8">
<head>
<style>
  .container{
    width:250px;
    height:250px;
    margin:20px auto 0 auto;

    display:flex;
    align-items: center;
    justify-content: center;
  }

  .react-logo{
    display: inline-block;
    border-radius:50%;
    border:10px solid #00d8ff;

    animation-name:rotate;
    animation-duration: 5s;
    animation-iteration-count: infinite;
    animation-timing-function: linear;

  }

  .react-logo , .react-logo:before , .react-logo:after{
    position:absolute;
    display: inline-block;
    width:200px;
    height:70px;
    border-radius:50%;
    border:10px solid #00d8ff;
  }

  .nucleo , .react-logo , .react-logo:before , .react-logo:after {
    display: flex;
    align-items: center;
    justify-content: center;
  }

  .nucleo{
    width:40px;
    height:40px;
    border-radius:100%;
    background:#00d8ff;
  }

  .react-logo:before , .react-logo:after{
    content:"";
  }

  .react-logo:after{
    transform:rotate(-57deg);
  }

  .react-logo:before{
    transform:rotate(57deg);
  }
  
.title{
  font-size:60px;
  background:#222;
  color:#00d8ff;
  width:250px;
  margin:2px auto;
  text-align:center;
}

  @keyframes rotate{

    100%{
      transform:rotate(360deg);
    }
  }

</style>
</head>
<div class="container">
		<span class="react-logo">
			<span class="nucleo"></span>
		</span>
   
</div>

<h1 align="center">
    <img id="gif" alt="gif ThemeSwitcher" title="#ThemeSwitcher" src=".github/first_dark-mode.gif" width="600px" />
</h1>

<h4 align="center">
  ThemeSwitcher
</h4>

<p align="center">
 <img src="https://img.shields.io/static/v1?label=PRs&message=welcome&color=101010&labelColor=1C1C1C" alt="PRs welcome!" />

  <img alt="License" src="https://img.shields.io/static/v1?label=license&message=MIT&color=101010&labelColor=1C1C1C">
</p>
<p align="center">
<!-- <a href="https://github.com/joaobispo2077" target="_blank">
    <img alt="Made by João Bispo" src="https://img.shields.io/static/v1?label=Made%20By&message=Joao%20Bispo&color=1E90FF&labelColor=1C1C1C"">
  </a> -->
  <a href="https://github.com/joaobispo2077" target="_blank" >
    <img alt="Github - João Bispo" src="https://img.shields.io/badge/Github--%4B0082?style=plastic&labelColor=1C1C1C&color=101010&logo=github">
  </a>
  <a href="https://www.linkedin.com/in/joão-bispo-2077/" target="_blank" >
    <img alt="Linkedin - João Bispo" src="https://img.shields.io/badge/Linkedin--%23F8952D?style=plastic&labelColor=1C1C1C&color=101010&logo=linkedin">
  </a>
  <a href="mailto:joaobispo2077@gmail.com" target="_blank" >
    <img alt="Email - João Bispo" src="https://img.shields.io/badge/Email--%23F8952D?style=plastic&labelColor=1C1C1C&color=101010&logo=gmail">
  </a>
</p>

<p align="center">
  <a href="#rocket-technology">Technology</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-project">Project</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-layout">Layout</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#-how-to-contribute">How to contribute</a>&nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#memo-license">License</a>
</p>

<br>

<!-- <p align="center">
  <img alt="Proffy Previw" src=".github/proffy.png" width="100%">
</p> -->

## :rocket: Technology

This project was developed with the following technologies:

- [React](https://reactjs.org)
- [TypeScript](https://www.typescriptlang.org)


## 💻 Project

The ThemeSwitcher is a project to pratice the creation of darkmode using React.Js and Typescript.

## 🔖 Layout
<a href="#gif">Darkmode</a>

## ♻️ How to contribute

- Fork this repository;
- Create a branch with your feature: `git checkout -b my-feature`;
- Commit your changes: `git commit -m 'feat: My new feature'`;
- Push to your branch: `git push origin minha-feature`.

After the merge of your pull request is done, you can delete your branch.

<!-- ## :memo: License

This project is under the MIT license. See the [LICENSE](LICENSE.md) file for more details. -->

---

<p align="center">Made with ♥ and ☕  by <strong><a href="https://www.linkedin.com/in/joão-bispo-2077/">João Bispo</a> 😎</strong> </p>