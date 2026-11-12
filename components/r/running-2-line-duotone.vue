<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><circle class="c20ejs7zg"/><path class="pek1alrpa"/><path class="ki8a531mw"/><path class="hsbnu6mgm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:running-2-line-duotone" /></template>
<style>
.c20ejs7zg {
  cx: 18.5px;
  cy: 4.5px;
  r: 2.5px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

.hsbnu6mgm {
  stroke-linejoin: round;
  d: path("M4 9.63634L5.43568 8.82061C7.87566 7.43426 9.09566 6.74108 10.4467 6.64283C11.4679 6.56857 12.0528 6.79985 13.4066 7.35713C14.4288 7.77789 15.2738 8.54745 15.7681 9.53616C16.5231 11.0461 18.0664 12 19.7546 12H21");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ki8a531mw {
  d: path("M14.3993 22V19.939C14.3993 19.1454 14.3993 18.7486 14.3053 18.3819C14.2004 17.9733 14.0107 17.5914 13.7483 17.2612C13.5127 16.9647 13.1964 16.7251 12.5639 16.2459C11.6083 15.5219 11.1305 15.16 10.921 14.7202C10.6886 14.2323 10.6635 13.6712 10.8514 13.1646C11.0207 12.7078 12.112 11.8065 12.999 11.0001");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.pek1alrpa {
  d: path("M9 17L7.99923 18.2009C7.262 19.0856 6.89338 19.5279 6.38945 19.764C5.88552 20 5.30973 20 4.15813 20H3");
}

</style>
