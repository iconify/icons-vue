<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p-tmbkblw"/><path class="v0gg2detc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:programme-schedule" /></template>
<style>
.p-tmbkblw {
  d: path("M3 4.5h18V21H3Zm5-2V6m8-3.5V6M3 9.5h18");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v0gg2detc {
  d: path("M13.5 13.5H18v4h-4.5Z");
}

</style>
