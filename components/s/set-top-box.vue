<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="xm7c2-bof"/><path class="k6n_hdb4q"/><path class="xddmfbgnf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:set-top-box" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k6n_hdb4q {
  fill: currentColor;
  d: path("M6.5 11h.01");
}

.xddmfbgnf {
  d: path("M10 11h8");
}

.xm7c2-bof {
  d: path("M6 6.5h12a3.5 3.5 0 0 1 3.5 3.5v2a3.5 3.5 0 0 1-3.5 3.5H6A3.5 3.5 0 0 1 2.5 12v-2A3.5 3.5 0 0 1 6 6.5m-.5 9V18m13-2.5V18");
}

</style>
