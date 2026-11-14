<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sv7te_rfq"/><path class="wmm_k3b3u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:theme-palette" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sv7te_rfq {
  d: path("M12 2.5a9.5 9.5 0 0 0 0 19c1.5 0 2.25-1 2-2.25s-.5-2 .5-2.75c.75-.5 1.5-.5 2.5-.5h1a3.5 3.5 0 0 0 3.5-3.5c0-5.5-4.25-10-9.5-10");
}

.wmm_k3b3u {
  d: path("M6.5 12a1 1 0 1 0 2 0a1 1 0 1 0-2 0M8 7.5a1 1 0 1 0 2 0a1 1 0 1 0-2 0m5-.75a1 1 0 1 0 2 0a1 1 0 1 0-2 0M16.5 10a1 1 0 1 0 2 0a1 1 0 1 0-2 0");
}

</style>
