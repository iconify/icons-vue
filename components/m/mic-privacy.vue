<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="f6zd1bc-x"/><path class="v_bfcib-d"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:mic-privacy" /></template>
<style>
.f6zd1bc-x {
  d: path("M8.75 3za2.75 2.75 0 0 1 2.75 2.75v4.5A2.75 2.75 0 0 1 8.75 13A2.75 2.75 0 0 1 6 10.25v-4.5A2.75 2.75 0 0 1 8.75 3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.v_bfcib-d {
  d: path("M3.5 10.5a5 5 0 0 0 10.5 0m-5.25 5V20m-3 0h6m5-3h2.5A1.75 1.75 0 0 1 21 18.75v1a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 15 19.75v-1A1.75 1.75 0 0 1 16.75 17m-.5 0v-1.25a1.75 1.75 0 0 1 3.5 0V17");
}

</style>
