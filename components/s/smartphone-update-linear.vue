<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVG6WNJNcPe)" class="caog0qvka"><path class="yncpr3b3n"/><path class="cw0dg-bgf"/><path class="erekrcbav"/></g><defs><clipPath id="SVG6WNJNcPe"><rect class="fng6irbns"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:smartphone-update-linear" /></template>
<style>
.caog0qvka {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.cw0dg-bgf {
  stroke-linejoin: round;
  d: path("M2.73016 4.8L2.73016 4C2.73016 1.79086 4.36469 0 6.38098 0C7.47451 0 8.45575 0.526765 9.12484 1.36133M2 4L2.73016 4.8L3.46033 4M10.2698 3.2V4C10.2698 6.20914 8.63531 8 6.61902 8C5.60133 8 4.68089 7.54376 4.0188 6.80778M11 4L10.2698 3.2L9.53967 4");
}

.erekrcbav {
  d: path("M15 19H9");
}

.fng6irbns {
  width: 24px;
  height: 24px;
  fill: var(--svg-color--fff, #fff);
}

.ft5dv1b6b {
  fill: none;
}

.yncpr3b3n {
  d: path("M13 2.00098C16.1143 2.01009 17.7653 2.10853 18.8284 3.17162C20 4.34319 20 6.22881 20 10V14C20 17.7713 20 19.6569 18.8284 20.8285C17.6569 22 15.7712 22 12 22C8.22876 22 6.34315 22 5.17157 20.8285C4 19.6569 4 17.7713 4 14V11.001");
}

</style>
