<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="splv_iblx"/><path class="yz_g7_bzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:recipient-id-check" /></template>
<style>
.splv_iblx {
  d: path("M3 5.5h18v13H3Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.yz_g7_bzn {
  d: path("M5.75 11a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0ZM13 9.5h5M13 13h3");
}

</style>
