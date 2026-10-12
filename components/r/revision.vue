<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="y_xkwfaps"/><path class="c1ohgwboi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:revision" /></template>
<style>
.c1ohgwboi {
  d: path("M21.25 17a4 4 0 1 1-4-4m-1.5-1.5l1.5 1.5l-1.5 1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y_xkwfaps {
  d: path("M11 20.25H6.25a1.5 1.5 0 0 1-1.5-1.5V5.25a1.5 1.5 0 0 1 1.5-1.5h8l4 4v2.5m-4-6.5v4h4M8 11h4.5");
}

</style>
