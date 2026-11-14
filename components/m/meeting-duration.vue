<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="p-tmbkblw"/><path class="gg5d-9bwa"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:meeting-duration" /></template>
<style>
.gg5d-9bwa {
  d: path("M9.25 12.75L7 15l2.25 2.25M7 15h10m-2.25-2.25L17 15l-2.25 2.25");
}

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

</style>
