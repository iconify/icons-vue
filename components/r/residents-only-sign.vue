<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xhw75ibjv"/><path class="tob9ffb0a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:residents-only-sign" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tob9ffb0a {
  d: path("M7 11.5V9.314a1.5 1.5 0 0 1 .683-1.258l3.5-2.275a1.5 1.5 0 0 1 1.634 0l3.5 2.275A1.5 1.5 0 0 1 17 9.314V11.5a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 7 11.5");
}

.xhw75ibjv {
  d: path("M7.375 2.5h9.25A4.375 4.375 0 0 1 21 6.875v4.75A4.375 4.375 0 0 1 16.625 16h-9.25A4.375 4.375 0 0 1 3 11.625v-4.75A4.375 4.375 0 0 1 7.375 2.5M12 16v5.5");
}

</style>
