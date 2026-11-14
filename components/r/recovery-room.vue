<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="uhificc1j"/><path class="qcxqkw8dv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:recovery-room" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.qcxqkw8dv {
  d: path("M19 16h2.75v2.75");
}

.uhificc1j {
  d: path("M3 3.5v13m1.625-7h10.75A1.625 1.625 0 0 1 17 11.125a1.625 1.625 0 0 1-1.625 1.625H4.625A1.625 1.625 0 0 1 3 11.125A1.625 1.625 0 0 1 4.625 9.5m1.25-3.25h2.25A1.125 1.125 0 0 1 9.25 7.375A1.125 1.125 0 0 1 8.125 8.5h-2.25A1.125 1.125 0 0 1 4.75 7.375A1.125 1.125 0 0 1 5.875 6.25M16 12.75v1.75M14.25 21L17 18l2 1.75l2.5-3.5");
}

</style>
