<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="y-aluxb2e"/><path class="l0cbzabqo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:user-list" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l0cbzabqo {
  d: path("M3.5 20.25h11a.75.75 0 0 0 .75-.75c0-2.9-2.7-5-6.25-5s-6.25 2.1-6.25 5a.75.75 0 0 0 .75.75M15 4.5a3.5 3.5 0 0 1 0 7m2.5 3.25c2.15.6 3.75 2.2 3.75 4.25v.5a.75.75 0 0 1-.75.75H19");
}

.y-aluxb2e {
  cx: 9px;
  cy: 8px;
  r: 3.5px;
}

</style>
