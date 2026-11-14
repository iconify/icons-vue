<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="qho9yybwl"/><path class="mmv3afb7j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:ok-gesture" /></template>
<style>
.mmv3afb7j {
  d: path("M20 12.5v3a6 6 0 0 1-6 6c-2.5 0-3.75-2.5-3.75-5.25M14 12V4.5m3 7.5V3.5m3 9v-7");
}

.qho9yybwl {
  d: path("M4.75 14a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
