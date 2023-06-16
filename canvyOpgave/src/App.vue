<script setup>
import Rectangle8 from '@/assets/Rectangle 8.png'
import Rectangle11 from '@/assets/Rectangle 11.png'
import Rectangle13 from '@/assets/Rectangle 13.png'
import Rectangle14 from '@/assets/Rectangle 14.png'
import Rectangle16 from '@/assets/Rectangle 16.png'
import Rectangle19 from '@/assets/Rectangle 19.png'
import Rectangle26 from '@/assets/Rectangle 26.png'
import Component30 from '@/assets/Component 30.svg'
import g338 from '@/assets/g338.svg'
import Group17 from '@/assets/Group 17.svg'
import path98 from '@/assets/path98.svg'
import path154 from '@/assets/path154.svg'
import path322 from '@/assets/path322.svg'
import group4 from '@/assets/Group 4.svg'
import path70 from '@/assets/path70.svg'

</script>

<template>
  <header> </header>

  <main>
    <div class="container">
      <img :src="Component30" class="component30a-svg">
      
      <div class="about-me">
        <img :src="path154" class="path154-svg">
        <img :src="Group17" class="group17-svg">
        <img :src="Component30" class="component30b-svg">
        <img :src="Path70" class="path70.svg">
        <img :src="Path322" class="path322.svg">
        <div class="about-me-content">
          <img :src="Rectangle26" class="about-me-image">
          <h1>Sara Pilasco</h1>
          <p>Flower and power is my main motto when it comes to paint and art</p>
          <h2>Paintings</h2>
          <h2>Sculptures</h2>
          <h2>Collections</h2>
          <h2>Bio</h2>
          <h2>Contact</h2>
          <img :src="group4" class="group4-svg">
          <img :src="path98" class="path98-svg">
          <img :src="g338" class="g338-svg">
          <img :src="path322" class="path322-svg">
          <img :src="path70" class="path70-svg">
        </div>
      </div>
      <div class="image-Gallery">
        <div class="column">
          <img :src="Rectangle8" class="gallery-image">
          <img :src="Rectangle13" class="gallery-image">
          <img :src="Rectangle14" class="gallery-image">
        </div>
        <div class="column">
          <img :src="Rectangle11" class="gallery-image">
          <img :src="Rectangle16" class="gallery-image">
          <img :src="Rectangle19" class="gallery-image">
        </div>
      </div>
    </div>
    <TheWelcome />
  </main>
</template>

<style>
@import url('https://fonts.googleapis.com/css2?family=Baloo+2:wght@800&family=Roboto:wght@100&display=swap');
body {
  margin: 0;
  padding: 0;
  background-color: white;
  z-index: -2;
}

.container {
  display: flex;
  flex-direction: row;
  align-items: flex-start;
  width: 1194px;
  margin: 0 auto;
  position: relative;
}

.about-me {
  width: 20%;
  overflow: visible;
  box-sizing: border-box;
}


.about-me-content {
  width: 68%;
  text-align: left;
  z-index: 2;
  overflow: visible;
  
}

.component30a-svg {
  position: absolute;
  top: -120px; 
  right: 20px; 
  z-index: 1; 
}
.component30b-svg {
  position: absolute;
  top: 375px; 
  left: -15px; 
  z-index: -1; 
}
.g338-svg{
  position: absolute;
}
.group4-svg{
  position: absolute;
  margin-top: 10px;
}
.g338-svg{
  position: absolute;
  left: 50px;
  top: 830px;
}
.group17-svg{
  position: absolute;
  z-index: 1;
  left: 165px;
  top: 230px;
}
.path98-svg{
  position: relative;
  top: 40px;
  
}
.path322-svg{
  position: absolute;
  width: 246px;
  height: 128px;
  left:-60px;
  top:925px;
  transform: rotate(120deg);
}

.path70-svg {
  position: absolute;
  left: 0px;
  top: 880px;
}
.path154-svg{
  position: absolute;
  overflow:visible ;
  left: -20px;
  top: 150px;
}

.image-Gallery {
  width: 80%;
  overflow-y: auto;
  display: flex;
}

.column {
  width: calc(50% - 10%); 
  margin-right: 20px;
}


.column:last-child {
  margin-right: 0;
}

.gallery-image {
  width: 100%; 
  height: auto; 
  border-radius: 5px;
  display: block;
  margin-top: 20px;
  position: relative;
  z-index: 2; 
  
}

.about-me-image {
  width: 130%; 
  height: auto; 
  border-radius: 5px; 
  margin-top: 1.5px;
  z-index: 0;
}

h1 {
  text-transform: uppercase;
  font-family: 'Baloo 2', cursive;
  font-weight: bold;
  line-height: 0.9;
  font-size: 38px;
  margin-bottom: 2px; 
}

p {
  font-weight: bold;
  font-size: 16px; 
  line-height: 1.2; 
  font-family: 'Roboto', sans-serif;
  color: rgba(128, 128, 128, 0.8);
}

h2 {
  text-transform:uppercase;
  font-family: 'Baloo 2', cursive;
  font-weight: bold;
  line-height: 1.0;
  font-size: 19px; 
}

</style>
