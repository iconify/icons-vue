<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="vxhjkt3nv"/><path class="l6bdajbyh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:pin-antiques" /></template>
<style>
.l6bdajbyh {
  d: path("M9 5C5.5 5 4.5 7.5 6 9.5M14 5c3.5 0 4.5 2.5 3 4.5M18 21l-2.25-3.25a3.25 3.25 0 1 1 4.5 0Z");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vxhjkt3nv {
  d: path("M13.937 20H8.5c-1-.5-3.5-3-3.5-6.5C5 9 9 7 9 5V3h5v2c0 1.265 1.601 2.53 2.777 4.428");
}

</style>
