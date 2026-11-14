<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="a2boy5z0z"/><path class="e14_c9bss"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rain-fly" /></template>
<style>
.a2boy5z0z {
  d: path("M12.906 20.5H3.5L12 7l3.755 5.963");
}

.e14_c9bss {
  d: path("M2.5 12L12 3.5l9.5 8.5M12 13.5v7m6.5-6.5c2 2.25 3 3.5 3 4.75a3 3 0 0 1-6 0c0-1.25 1-2.5 3-4.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
