<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="g65mw9-lk"/><path class="h-wfj2ban"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pin-kayak" /></template>
<style>
.g65mw9-lk {
  d: path("M2.5 12C7 8.5 17 8.5 21.5 12C17 15.5 7 15.5 2.5 12M7 7l10 10");
}

.h-wfj2ban {
  fill: currentColor;
  d: path("M3.055 3.055za1.25 1.25 0 0 1 1.768 0l2.122 2.122a1.25 1.25 0 0 1 0 1.768a1.25 1.25 0 0 1-1.768 0L3.055 4.823a1.25 1.25 0 0 1 0-1.768m14 14za1.25 1.25 0 0 1 1.768 0l2.122 2.122a1.25 1.25 0 0 1 0 1.768a1.25 1.25 0 0 1-1.768 0l-2.122-2.122a1.25 1.25 0 0 1 0-1.768");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
