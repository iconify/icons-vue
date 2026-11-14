<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hjp0op5-z"/><path class="ex51uob0j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:motorway-sign" /></template>
<style>
.ex51uob0j {
  d: path("M12 11.5v-6M9.5 8L12 5.5L14.5 8");
}

.hjp0op5-z {
  d: path("M2.5 2.5h19v12h-19Zm4.5 12v7m10-7v7");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
