<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="fg8nb-p7y"/><path class="u_s45c74p"/><path class="jtlp82emg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:time-series-db" /></template>
<style>
.fg8nb-p7y {
  d: path("M3.5 3v17.5H12");
}

.jtlp82emg {
  d: path("M15 16v4a3.5 1.5 0 0 0 7 0v-4");
}

.u_s45c74p {
  d: path("m6.5 15.5l3.5-4l2.567 1.711m.672-.005L19.5 5.5M15 16a3.5 1.5 0 1 0 7 0a3.5 1.5 0 1 0-7 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
