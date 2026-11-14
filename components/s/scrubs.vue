<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="sw24vsbsh"/><path class="fz5z-nxec"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:scrubs" /></template>
<style>
.fz5z-nxec {
  d: path("M13 13h3v3.5h-3Z");
}

.sw24vsbsh {
  d: path("m9 3l3 4l3-4l6 3l-2 4.5l-2-1v11H7v-11l-2 1L3 6Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
