<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="g01zyvbwi"/><path class="m6m3xpbtb"/><path class="tmuowpwde"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:sun-halo-outline-regular" /></template>
<style>
.g01zyvbwi {
  d: path("M7.5 12a4.5 4.5 0 1 0 9 0 4.5 4.5 0 1 0 -9 0");
}

.m6m3xpbtb {
  d: path("M3.54 8.92a9 9 0 0 1 16.92 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.tmuowpwde {
  d: path("M20.46 15.08a9 9 0 0 1 -16.92 0");
}

</style>
