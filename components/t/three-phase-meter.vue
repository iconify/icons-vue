<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="o2uygihlr"/><path class="mo6d_r6_w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:three-phase-meter" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mo6d_r6_w {
  d: path("M10 5.5h4A1.5 1.5 0 0 1 15.5 7A1.5 1.5 0 0 1 14 8.5h-4A1.5 1.5 0 0 1 8.5 7A1.5 1.5 0 0 1 10 5.5m-1 6v4m3-4v4m3-4v4");
}

.o2uygihlr {
  d: path("M3.25 11a8.75 8.75 0 1 0 17.5 0a8.75 8.75 0 1 0-17.5 0M12 19.75V22");
}

</style>
