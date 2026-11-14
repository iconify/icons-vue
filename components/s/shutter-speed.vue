<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="sl-h_-5_v"/><path class="x9477rebd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:shutter-speed" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sl-h_-5_v {
  d: path("M4.5 13.5a7.5 7.5 0 1 0 15 0a7.5 7.5 0 1 0-15 0M10 2.75h4m-2 0V6");
}

.x9477rebd {
  d: path("M8.25 13.5a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0M12 9.75l-1.75 7m5-1.5l-5-5m-1.5 5l7-1.75");
}

</style>
