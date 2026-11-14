<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ivfdabg1j"/><path class="kfk2zn8hp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:toy-drum" /></template>
<style>
.ivfdabg1j {
  d: path("M4.5 10a7.5 2.5 0 1 0 15 0a7.5 2.5 0 1 0-15 0Z");
}

.kfk2zn8hp {
  d: path("M4.5 10v7a7.5 2.5 0 0 0 15 0v-7M8 7.75l8.5-5.25M16 7.75L7.5 2.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
