<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ronik2b-p"/><path class="dhoe--bbr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pet-anaesthesia" /></template>
<style>
.dhoe--bbr {
  d: path("m5 4l6.5 3.5v3L5 14m6.5-5H14c3.5 0 6 2.5 6 6s-2.5 6-6 6");
}

.ronik2b-p {
  d: path("M3.25 9a1.75 5 0 1 0 3.5 0a1.75 5 0 1 0-3.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
