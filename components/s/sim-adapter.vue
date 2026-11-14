<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ke217hb5r"/><path class="a2p9d80_e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:sim-adapter" /></template>
<style>
.a2p9d80_e {
  d: path("M9.25 11h2.525a1.75 1.75 0 0 1 1.238.513l1.974 1.974a1.75 1.75 0 0 1 .513 1.238v2.025a1.75 1.75 0 0 1-1.75 1.75h-4.5a1.75 1.75 0 0 1-1.75-1.75v-4A1.75 1.75 0 0 1 9.25 11");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ke217hb5r {
  d: path("M8 2.5h5.05a3.5 3.5 0 0 1 2.475 1.025l2.95 2.95A3.5 3.5 0 0 1 19.5 8.95V18a3.5 3.5 0 0 1-3.5 3.5H8A3.5 3.5 0 0 1 4.5 18V6A3.5 3.5 0 0 1 8 2.5");
}

</style>
