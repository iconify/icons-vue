<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="wqi57sfeu"/><path class="ufrcmgz_u"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:routine-schedule" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.ufrcmgz_u {
  d: path("M16.75 8.75L19 11l2.25-2.25M8 11a3 3 0 1 0 6 0a3 3 0 1 0-6 0Zm6.75 7a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wqi57sfeu {
  d: path("M5.25 16.75A8 8 0 1 1 19 11");
}

</style>
