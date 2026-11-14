<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z5dlsod_v"/><path class="bn0xfh8xx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:visual-field-test" /></template>
<style>
.bn0xfh8xx {
  d: path("M10 15a2 2 0 1 0 4 0a2 2 0 1 0-4 0Zm-7.5-.5a9.5 9.5 0 0 1 .465-2.936m.808-1.814a9.5 9.5 0 0 1 1.87-2.31M7.25 6.273a9.5 9.5 0 0 1 2.775-1.065m.489-.091a9.5 9.5 0 0 1 2.972 0m.489.091a9.5 9.5 0 0 1 2.775 1.065m1.607 1.167a9.5 9.5 0 0 1 1.87 2.31m.808 1.814A9.5 9.5 0 0 1 21.5 14.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z5dlsod_v {
  d: path("M5.5 15c2-3.5 11-3.5 13 0c-2 3.5-11 3.5-13 0Z");
}

</style>
