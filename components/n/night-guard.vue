<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ra2e_hbzw"/><path class="eq3eudfrl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:night-guard" /></template>
<style>
.eq3eudfrl {
  d: path("M6.5 9.25c1 1.5 2.25 2 4 2s3-.5 4-2m4.5 5.5A3.5 3.5 0 1 0 21.5 19a2.75 2.75 0 0 1-2.5-4.25Z");
}

.ra2e_hbzw {
  d: path("M3 6c0 5.5 3.5 8 7.5 8S18 11.5 18 6a2.5 2.5 0 0 0-5 0a2.5 2.5 0 0 0-5 0a2.5 2.5 0 0 0-5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
