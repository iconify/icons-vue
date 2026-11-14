<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="v3telqbyv"/><path class="ubigrpy6s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:mood-slider" /></template>
<style>
.ubigrpy6s {
  d: path("M9.75 9a2.25 2.25 0 0 0 4.5 0M3 18.5h6.25m5.5 0H21m-11.75 0a2.75 2.75 0 1 0 5.5 0a2.75 2.75 0 1 0-5.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v3telqbyv {
  d: path("M6.5 7.5a5.5 5.5 0 1 0 11 0a5.5 5.5 0 1 0-11 0Zm3.5-1h.01m3.99 0h.01");
}

</style>
