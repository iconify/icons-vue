<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="bj6m0rp9b"/><circle class="vf78g51_u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:moon-phases" /></template>
<style>
.bj6m0rp9b {
  d: path("M13.75 4.58a8 8 0 1 0 0 14.84a8.5 8.5 0 0 1 0-14.84");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vf78g51_u {
  cx: 18.75px;
  cy: 12px;
  r: 2.5px;
}

</style>
