<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="miigo3bry"/><path class="a42ux9bpc"/><path class="ojjncdbgw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:pull-door-sign" /></template>
<style>
.a42ux9bpc {
  d: path("M11 12c-4.5 0-7 1.5-7 5.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.miigo3bry {
  d: path("M11.25 2.5h8.5a1.75 1.75 0 0 1 1.75 1.75v15.5a1.75 1.75 0 0 1-1.75 1.75h-8.5a1.75 1.75 0 0 1-1.75-1.75V4.25a1.75 1.75 0 0 1 1.75-1.75M15.5 7v10M13 7h2.5M13 17h2.5");
}

.ojjncdbgw {
  d: path("M2.5 16L4 17.5L5.5 16");
}

</style>
