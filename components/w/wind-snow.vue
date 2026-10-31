<script setup>
import { Icon } from '@iconify/css-vue';
import '../../css/v/vlk5ymyap.css';
import '../../css/i/i27tkhlqe.css';
import '../../css/x/xv2f7s87m.css';
import '../../css/p/pt3dsebxs.css';
import '../../css/h/h2tk_q-sp.css';

const props = defineProps(["width","height"]);

const viewBox = {"width":512,"height":512};
const content = `<defs><symbol id="SVGkG8Nrphp" viewBox="0 0 342 234"><path class="vlk5ymyap"><animate attributeName="stroke-dashoffset" dur="6s" repeatCount="indefinite" values="0; 2960"/></path><path class="i27tkhlqe"><animate attributeName="stroke-dashoffset" dur="6s" repeatCount="indefinite" values="0; 1540"/></path></symbol></defs><use width="342" height="234" href="#SVGkG8Nrphp" transform="translate(85 139)"/><path opacity="0" class="xv2f7s87m"><animateTransform id="SVGFQmdqcek" additive="sum" attributeName="transform" begin=".5s;SVGFQmdqcek.end+1.33s" dur="1.67s" type="translate" values="-30 0; 30 0"/><animate attributeName="opacity" begin=".5s;SVGFQmdqcek.end+1.33s" dur="1.67s" keyTimes="0; .2; .8; 1" values="0; 1; 1; 0"/></path><path opacity="0" class="pt3dsebxs"><animateTransform id="SVGOK15FbmV" additive="sum" attributeName="transform" begin="1s;SVGOK15FbmV.end+1.33s" dur="1.67s" type="translate" values="-30 0; 30 0"/><animate attributeName="opacity" begin="1s;SVGOK15FbmV.end+1.33s" dur="1.67s" keyTimes="0; .2; .8; 1" values="0; 1; 1; 0"/></path><path opacity="0" class="h2tk_q-sp"><animateTransform id="SVG8BRUM5DK" additive="sum" attributeName="transform" begin="0s;SVG8BRUM5DK.end+1.33s" dur="1.67s" type="translate" values="-30 0; 30 0"/><animate attributeName="opacity" begin="0s;SVG8BRUM5DK.end+1.33s" dur="1.67s" keyTimes="0; .2; .8; 1" values="0; 1; 1; 0"/></path>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="meteocons:wind-snow" /></template>
