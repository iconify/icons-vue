<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n-d29-b6s"/><path class="cjn950buu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:programme-schedule" /></template>
<style>
.cjn950buu {
  d: path("M15.25 13.5h1A1.75 1.75 0 0 1 18 15.25v.5a1.75 1.75 0 0 1-1.75 1.75h-1a1.75 1.75 0 0 1-1.75-1.75v-.5a1.75 1.75 0 0 1 1.75-1.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.n-d29-b6s {
  d: path("M6.5 4.5h11A3.5 3.5 0 0 1 21 8v9.5a3.5 3.5 0 0 1-3.5 3.5h-11A3.5 3.5 0 0 1 3 17.5V8a3.5 3.5 0 0 1 3.5-3.5m1.5-2V6m8-3.5V6M3 9.5h18");
}

</style>
