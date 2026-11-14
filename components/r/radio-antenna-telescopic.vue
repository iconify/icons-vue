<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="dg2ma0_7p"/><path class="ols36dwys"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:radio-antenna-telescopic" /></template>
<style>
.dg2ma0_7p {
  d: path("M2.5 9h19v11.5h-19Zm13 0L20 3");
}

.ols36dwys {
  d: path("M5.25 14.75a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0ZM13.5 13h5m-5 3.5h5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
