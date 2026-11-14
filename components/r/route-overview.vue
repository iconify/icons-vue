<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eoiz0rolg"/><path class="kqhw4bchn"/><path class="ba_952xdh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:route-overview" /></template>
<style>
.ba_952xdh {
  fill: currentColor;
  d: path("M16 9a1 1 0 1 0 2 0a1 1 0 1 0-2 0Z");
}

.eoiz0rolg {
  d: path("m3 6l6-2.5L15 6l6-2.5V18l-6 2.5L9 18l-6 2.5Z");
}

.kqhw4bchn {
  d: path("M7 15c2.5-6.5 7.5.5 10-6");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
