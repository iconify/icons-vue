<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e5pa8cqom"/><circle class="pp-dsr39e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:oyster-pearl" /></template>
<style>
.e5pa8cqom {
  d: path("M3.25 10C3.5 5.75 7.5 2.75 12.5 2.75c3 0 5.75.75 7.75 2Zm0 5.75h17.5c0 3.4-3.9 5.5-8.75 5.5s-8.75-2.1-8.75-5.5m5.25 1.5L9 19.5m3-2.25v3m3.5-3L15 19.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pp-dsr39e {
  cx: 12px;
  cy: 11.6px;
  r: 1.5px;
}

</style>
