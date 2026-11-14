<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ikk-jub3t"/><path class="q7eexkvah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shortboard" /></template>
<style>
.ikk-jub3t {
  d: path("M10.5 3.5C14.5 8 15 15 13 20.5H8C6 15 6.5 8 10.5 3.5Z");
}

.q7eexkvah {
  d: path("m14 14l3.5 4.5l-3.75-.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
