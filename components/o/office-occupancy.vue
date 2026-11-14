<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rtplj4b2l"/><path class="bje6tlmsm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:office-occupancy" /></template>
<style>
.bje6tlmsm {
  fill: currentColor;
  d: path("M6.75 15h10.5A1.75 1.75 0 0 1 19 16.75v3a1.75 1.75 0 0 1-1.75 1.75H6.75A1.75 1.75 0 0 1 5 19.75v-3A1.75 1.75 0 0 1 6.75 15");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rtplj4b2l {
  d: path("M6.75 2.5h10.5A1.75 1.75 0 0 1 19 4.25v15.5a1.75 1.75 0 0 1-1.75 1.75H6.75A1.75 1.75 0 0 1 5 19.75V4.25A1.75 1.75 0 0 1 6.75 2.5m-4.25 19H5m14 0h2.5m-13-16h.01m3.49 0h.01m3.49 0h.01M8.5 8.75h.01m3.49 0h.01m3.49 0h.01M8.5 12h.01M12 12h.01m3.49 0h.01");
}

</style>
