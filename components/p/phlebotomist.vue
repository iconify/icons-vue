<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="x9err8bwn"/><path class="pbeiyabda"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:phlebotomist" /></template>
<style>
.pbeiyabda {
  fill: currentColor;
  d: path("M16.25 17.5h3.5v2c0 2.25-3.5 2.25-3.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x9err8bwn {
  d: path("M13.572 20.5H4c-.6 0-1-.4-1-1c0-3.25 3.25-5.5 7.5-5.5c.682 0 1.339.058 1.96.169M6.5 7a4 4 0 1 0 8 0a4 4 0 1 0-8 0Zm9.75 7.25v5.25c0 2.25 3.5 2.25 3.5 0v-5.25m-4.5 0h5.5");
}

</style>
