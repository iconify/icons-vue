<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wodz3xbms"/><path class="jbcs6l8jv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:type-outline" /></template>
<style>
.jbcs6l8jv {
  d: path("M10.25 13L12 8.25L13.75 13Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wodz3xbms {
  d: path("m3.5 20.5l6.5-17h4l6.5 17h-4l-1.5-4H9l-1.5 4Z");
}

</style>
