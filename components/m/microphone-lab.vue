<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="jkfcq5bgn"/><path class="lfy8rmb1d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:microphone-lab" /></template>
<style>
.jkfcq5bgn {
  d: path("M7.5 2.5h4a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1h-4a1 1 0 0 1-1-1v-8a1 1 0 0 1 1-1Z");
}

.lfy8rmb1d {
  d: path("M3.75 9.5a5.75 5.75 0 0 0 11.5 0M9.5 15.25V21m-3 0h6m3-3.5V20m3-4.5v6m3-4V20");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
