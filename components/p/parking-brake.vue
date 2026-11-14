<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="nu6j2ybdj"/><path class="r6t8z9bxl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:parking-brake" /></template>
<style>
.nu6j2ybdj {
  d: path("M5.5 12a6.5 6.5 0 1 0 13 0a6.5 6.5 0 1 0-13 0Zm4.75 3.5v-7");
}

.r6t8z9bxl {
  d: path("M10.25 8.5h2.5a2 2 0 0 1 0 4h-2.5m-3.699 7.282a9.5 9.5 0 0 1 0-15.564m10.898 0a9.5 9.5 0 0 1 0 15.564");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
