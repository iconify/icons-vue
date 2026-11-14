<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="ghs1vwnec"/><path class="nwnt7_gdu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:stdout" /></template>
<style>
.ghs1vwnec {
  d: path("M16.5 14.8V20h-14V4h14v5.2");
}

.nwnt7_gdu {
  d: path("M5.5 9L8 11.5L5.5 14m5.5-2h10.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
