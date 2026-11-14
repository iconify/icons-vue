<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vqhld8jmn"/><path class="afcml7o4m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sand-castle" /></template>
<style>
.afcml7o4m {
  d: path("M10.5 20.5v-3a1.5 1.5 0 0 1 3 0v3M12 12V4m1.118.559l.132.066a.699.699 0 0 1 0 1.25l-.132.066A.773.773 0 0 1 12 5.25a.773.773 0 0 1 1.118-.691");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vqhld8jmn {
  d: path("M3.5 19V8.875A.875.875 0 0 1 4.375 8a.875.875 0 0 1 .875.875V9a1 1 0 0 0 1 1a1 1 0 0 0 1-1v-.125A.875.875 0 0 1 8.125 8A.875.875 0 0 1 9 8.875V10.5a1.5 1.5 0 0 0 1.5 1.5h3a1.5 1.5 0 0 0 1.5-1.5V8.875A.875.875 0 0 1 15.875 8a.875.875 0 0 1 .875.875V9a1 1 0 0 0 1 1a1 1 0 0 0 1-1v-.125A.875.875 0 0 1 19.625 8a.875.875 0 0 1 .875.875V19a1.5 1.5 0 0 1-1.5 1.5H5A1.5 1.5 0 0 1 3.5 19");
}

</style>
