<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="jfr0ecbcw"/><path class="qh26tccdq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mosque" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jfr0ecbcw {
  d: path("M2.75 21.25V7.5L4 4.5l1.25 3v13.75Zm16 0V7.5l1.25-3l1.25 3v13.75Zm-10.5 0V14.5a1 1 0 0 1 1-1h.25c0-3 2.5-4.25 2.5-7.5c0 3.25 2.5 4.5 2.5 7.5h.25a1 1 0 0 1 1 1v6.75ZM12 6V3");
}

.qh26tccdq {
  d: path("M10.75 21.25V19a1.25 1.25 0 0 1 2.5 0v2.25");
}

</style>
