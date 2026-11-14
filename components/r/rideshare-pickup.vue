<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vrd045n-g"/><path class="t1-3fvbih"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:rideshare-pickup" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.t1-3fvbih {
  d: path("M5 16.5a2 2 0 1 0 4 0a2 2 0 1 0-4 0m10 0a2 2 0 1 0 4 0a2 2 0 1 0-4 0M5.5 10h13M12 5.5V10");
}

.vrd045n-g {
  d: path("M2.5 14.5V11q0-1 1-1h2l3-4.5H15l3.5 4.5h2q1 0 1 1v3.5Z");
}

</style>
