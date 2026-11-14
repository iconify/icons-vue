<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="z0r29d8af"/><path class="m7oi74iev"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:wifi-zone-sign" /></template>
<style>
.m7oi74iev {
  d: path("M9.75 9.5a3 3 0 0 1 4.5 0m-6.5-2.25a6 6 0 0 1 8.5 0");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z0r29d8af {
  d: path("M3.5 2.5h17v12h-17Zm8.5 12v7m0-10h.01");
}

</style>
