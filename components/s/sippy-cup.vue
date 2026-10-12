<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="m_cwecbvd"/><path class="qbz-2p__y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sippy-cup" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.m_cwecbvd {
  d: path("M10 6.25V4.5a1.75 1.75 0 0 1 1.75-1.75h.5A1.75 1.75 0 0 1 14 4.5v1.75ZM7 10V7.5a1.25 1.25 0 0 1 1.25-1.25h7.5A1.25 1.25 0 0 1 17 7.5V10Zm.75 0h8.5l-.75 9.25a2 2 0 0 1-2 1.75h-3a2 2 0 0 1-2-1.75Z");
}

.qbz-2p__y {
  d: path("M7.95 12.5H6a1 1 0 0 0-1 1v2a1 1 0 0 0 1 1h2.28m7.77-4H18a1 1 0 0 1 1 1v2a1 1 0 0 1-1 1h-2.28");
}

</style>
