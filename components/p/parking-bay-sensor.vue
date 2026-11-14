<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="gb5i19bsq"/><path class="q-imo15wm"/><path class="dxrobyi0r"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:parking-bay-sensor" /></template>
<style>
.dxrobyi0r {
  d: path("M8.995 11.995a4.25 4.25 0 0 1 6.01 0M6.873 9.873a7.25 7.25 0 0 1 10.254 0");
}

.gb5i19bsq {
  d: path("M4 5v15h16V5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.q-imo15wm {
  fill: currentColor;
  d: path("M10.5 15a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0");
}

</style>
