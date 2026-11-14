<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hbcq3ebre"/><path class="iiqrlwb4i"/><path class="klpxmi3an"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:phone-clock" /></template>
<style>
.hbcq3ebre {
  d: path("M8.5 3.5c.8 0 1.3.5 1.5 1.25l.75 3c.15.75-.15 1.35-.75 1.75l-1.5 1c1.2 2.5 2.4 3.8 5 5l1-1.5c.4-.6 1-.9 1.75-.75l3 .75c.75.2 1.25.7 1.25 1.5v3c0 1.1-.9 2-2 2c-8 0-15-7-15-15c0-1.1.9-2 2-2Z");
}

.iiqrlwb4i {
  d: path("M14 6.5a3.5 3.5 0 1 0 7 0a3.5 3.5 0 1 0-7 0Z");
}

.klpxmi3an {
  d: path("M17.5 5v1.5l1.25 1");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
