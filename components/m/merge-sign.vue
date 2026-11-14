<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="c6tf4ybzp"/><path class="d0h1ckbhm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:merge-sign" /></template>
<style>
.c6tf4ybzp {
  d: path("m15.055 7.967l3.535 6.326a3.5 3.5 0 0 1-3.055 5.207h-7.07a3.5 3.5 0 0 1-3.055-5.207l3.535-6.326a3.5 3.5 0 0 1 6.11 0M12 8.5v8");
}

.d0h1ckbhm {
  d: path("M8.5 16.5V15c0-2 3.5-2.5 3.5-4.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
