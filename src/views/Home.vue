<template>
  <div id="slider" class="ccslider">
		<div class="slider-innerWrapper">
			<img src="../assets/images/slide01.jpg" alt="" data-transition="{ effect :  cubeUp ,  slices : 3,  animSpeed : 1200,  delay : 100,  delayDir :  fromCentre ,  easing :  easeInOutBack ,  depthOffset : 300,  sliceGap : 30}">
			<img src="../assets/images/slide02.jpg" alt="" data-transition="{ effect :  cubeRight ,  slices : 1,  delay : 200}">
			<img src="../assets/images/slide03.jpg" alt="" data-transition="{ effect :  cubeDown ,  slices : 1,  animSpeed : 3000,  delay : 30,  easing :  easeInOutElastic ,  depthOffset : 200,  sliceGap : 20}">
			<img src="../assets/images/slide04.jpg" alt="" data-transition="{ effect :  cubeLeft ,  slices : 3,  delay : 200,  delayDir :  toCentre }">
		</div>
		<div class="slider-controls">
			<a class="slider-nav prev"></a>
			<a class="slider-nav next"></a>
		</div>
		<ul class="control-links">
			<li data-index="0" class="active">1</li>
			<li data-index="1" class="">2</li>
			<li data-index="2" class="">3</li>
			<li data-index="3" class="">4</li>
		</ul>
	</div>
</template>

<script>
import '../assets/js/jquery-1.7.1.min.js'
import '../assets/js/jquery.easing.1.3.min.js'
import '../assets/js/jquery.ccslider-2.0.1.min.js'
import '../assets/js/scrollbox.js'

export default {
  name: 'home',
  mounted () {
    console.log($)
  }
}
</script>
<style scoped>
 @import "../assets/css/ccslider.css";
 @import "../assets/css/custom.css";
</style>
