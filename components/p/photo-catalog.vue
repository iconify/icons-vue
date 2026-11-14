<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="um2y76vkj"/><path class="qb_u-9nqh"/><path class="hs4r6le7p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:photo-catalog" /></template>
<style>
.hs4r6le7p {
  d: path("M8 6.25V3.5h13.5v11h-2.75M5.5 17.25l3.5-4l3.5 4m.25-4.75h.01");
}

.qb_u-9nqh {
  d: path("M5.25 9V6.25h13.5v11H16");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.um2y76vkj {
  d: path("M2.5 9H16v11H2.5Z");
}

</style>
