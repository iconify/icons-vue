<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a2ye3bc7m"/><path class="wrill1b5x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:shift-schedule" /></template>
<style>
.a2ye3bc7m {
  d: path("M2.5 7.5H11v9H2.5Zm10.5 0h8.5v9H13Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wrill1b5x {
  d: path("M5 12a1.75 1.75 0 1 0 3.5 0A1.75 1.75 0 1 0 5 12Zm1.75-3.25v.5m0 5.5v.5m-3-3.25h.5m5 0h.5M18 9.5c-2 .5-2.75 3-1.75 4.5s3 1.75 4 .5c-1.75-.25-3-2.75-2.25-5Z");
}

</style>
