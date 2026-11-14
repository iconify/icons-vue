<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ea5rpw4fi"/><path class="a6k62accz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:vr-headset-clock" /></template>
<style>
.a6k62accz {
  d: path("M18 16.5V18l1.25 1");
}

.ea5rpw4fi {
  d: path("M5 5a2.5 2.5 0 0 1 2.5-2.5h9A2.5 2.5 0 0 1 19 5v3.5c0 2.25-1.5 3.5-3.25 3.5c-1.25 0-2.25-1.5-3.75-1.5S9.5 12 8.25 12C6.5 12 5 10.75 5 8.5ZM2 6.5h3m14 0h3M14.75 18a3.25 3.25 0 1 0 6.5 0a3.25 3.25 0 1 0-6.5 0");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
