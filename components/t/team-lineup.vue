<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nctxihvqt"/><path class="ibwsyvfua"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:team-lineup" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ibwsyvfua {
  d: path("M10 2.5h4A1.5 1.5 0 0 1 15.5 4A1.5 1.5 0 0 1 14 5.5h-4A1.5 1.5 0 0 1 8.5 4A1.5 1.5 0 0 1 10 2.5m-2 8h8m-8 4h8m-8 4h5");
}

.nctxihvqt {
  d: path("M8 4h8a3.5 3.5 0 0 1 3.5 3.5V18a3.5 3.5 0 0 1-3.5 3.5H8A3.5 3.5 0 0 1 4.5 18V7.5A3.5 3.5 0 0 1 8 4");
}

</style>
