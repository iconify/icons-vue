<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="uc9bpzbys"/><path class="t21y4qbzy"/><path class="ssv7v3bmp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:thermometer-hot" /></template>
<style>
.ssv7v3bmp {
  d: path("M7.25 6.5v10m8.25-13q1.5 1.75 0 3.5t0 3.5m4-7q1.5 1.75 0 3.5t0 3.5");
}

.t21y4qbzy {
  fill: currentColor;
  d: path("M5.25 16.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0Z");
}

.uc9bpzbys {
  d: path("M4.25 12.5v-7a3 3 0 0 1 6 0v7a5 5 0 1 1-6 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
