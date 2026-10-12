<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><circle class="g828vzbqg"/><path class="k6c-93bsc"/><rect class="ccb5v1bmb"/><path class="ump_bpbwl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:reception-desk" /></template>
<style>
.ccb5v1bmb {
  width: 18.5px;
  height: 8px;
  x: 2.75px;
  y: 13.25px;
  rx: 2px;
}

.g828vzbqg {
  cx: 12px;
  cy: 5px;
  r: 2.25px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k6c-93bsc {
  d: path("M6.75 13.25c.4-1.9 2.5-3 5.25-3s4.85 1.1 5.25 3Z");
}

.ump_bpbwl {
  d: path("M2.75 16.25h18.5");
}

</style>
