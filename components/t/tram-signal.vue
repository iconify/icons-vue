<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="v7fblmbuk"/><path class="ddu2hxk1f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:tram-signal" /></template>
<style>
.ddu2hxk1f {
  fill: currentColor;
  d: path("M10.75 11.5a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 1 0-2.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v7fblmbuk {
  d: path("M9.875 2.5h4.25A4.375 4.375 0 0 1 18.5 6.875v4.75A4.375 4.375 0 0 1 14.125 16h-4.25A4.375 4.375 0 0 1 5.5 11.625v-4.75A4.375 4.375 0 0 1 9.875 2.5M12 16v5.5m-3 0h6m-6-15h6");
}

</style>
