<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="tgh67sb7j"/><path class="dc-rd_bfo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:smart-farm" /></template>
<style>
.dc-rd_bfo {
  d: path("M7 15.75h5V21H7ZM14.5 6A3.5 3.5 0 0 1 18 9.5m-3.5-7a7 7 0 0 1 7 7");
}

.tgh67sb7j {
  d: path("m2.5 13.5l2.25-4L9 7.5l4 2l2.25 4V21H2.5Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
