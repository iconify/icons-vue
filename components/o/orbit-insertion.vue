<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="kse0ue7mz"/><path class="sx24b-bsk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:orbit-insertion" /></template>
<style>
.kse0ue7mz {
  d: path("M5.5 11a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0Z");
}

.sx24b-bsk {
  d: path("M3 21c1.5-3 2.5-6 2.5-10m-2.25 2.25L5.5 11l2.25 2.25M10.5 11a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
