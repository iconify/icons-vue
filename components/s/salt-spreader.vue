<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="e5edfibml"/><path class="fc6ujgbzk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:salt-spreader" /></template>
<style>
.e5edfibml {
  d: path("M8 15V6a1 1 0 0 1 1-1h6.5v3.5h3l3 3V15Z");
}

.fc6ujgbzk {
  d: path("M9 17a2 2 0 1 0 4 0a2 2 0 1 0-4 0m7.5 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-12-5h.01M3 15.5h.01m1.99 3h.01");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
