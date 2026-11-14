<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="do2r73b3h"/><path class="hrm_1_bou"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:syringe-pump" /></template>
<style>
.do2r73b3h {
  d: path("M2.5 13h19v8.5h-19Zm2-7.5H15V10H4.5Zm-2 2.25h2m10.5 0h4.25m0-2.25V10M7.5 5.5V7M10 5.5V7m-.25 3v3");
}

.hrm_1_bou {
  d: path("M5 15.5h6V19H5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
