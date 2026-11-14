<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="as1dxacva"/><path class="wrs0-fwww"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:tv-on" /></template>
<style>
.as1dxacva {
  d: path("M2.5 3.5h19v14h-19Zm5.5 17h8");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wrs0-fwww {
  d: path("M9 8a3.9 3.9 0 1 0 6 0m-3-1.5v4");
}

</style>
