<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="hpoyl6bva"/><path class="dmrkpqeas"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:skater-glide" /></template>
<style>
.dmrkpqeas {
  d: path("M11 21h6a1.5 1.5 0 0 0 1.5-1.5");
}

.hpoyl6bva {
  d: path("M11.5 4.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm2 5.25L13 14.5m-5-2l10.5-3M5 16.5l8-2l1 6.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
