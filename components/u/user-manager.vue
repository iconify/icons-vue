<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="peiztcc3b"/><path class="goxucdbmu"/><path class="ecswmxb9c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:user-manager" /></template>
<style>
.ecswmxb9c {
  d: path("M12 17.75za.69.69 0 0 1 .658.474l.339 1.017a1.15 1.15 0 0 1-.372 1.259a1 1 0 0 1-1.25 0a1.15 1.15 0 0 1-.372-1.259l.339-1.017A.69.69 0 0 1 12 17.75");
}

.goxucdbmu {
  d: path("M11.791 16.25h.418a.57.57 0 0 1 .541.75l-.092.276a.69.69 0 0 1-.658.474a.69.69 0 0 1-.658-.474L11.25 17a.57.57 0 0 1 .541-.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.peiztcc3b {
  d: path("M4 21v-1.5c0-3 2.75-4.75 5.75-5L12 16.25l2.25-1.75c3 .25 5.75 2 5.75 5V21ZM8 7.5a4 4 0 1 0 8 0a4 4 0 1 0-8 0");
}

</style>
