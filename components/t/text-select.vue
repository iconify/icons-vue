<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dr_8wdh7s"/><rect class="i-w5cxb4e"/><path class="ivhrv7pui"/><circle class="dpu0-e8pd"/><circle class="w2fp3ub6f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:text-select" /></template>
<style>
.dpu0-e8pd {
  cx: 6px;
  cy: 7.25px;
  r: 1.25px;
}

.dr_8wdh7s {
  d: path("M3.75 3.75h16.5m-16.5 16.5h10");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.i-w5cxb4e {
  width: 6px;
  height: 6.5px;
  x: 9px;
  y: 8.75px;
  rx: 1.5px;
}

.ivhrv7pui {
  d: path("M11 12h2M6 8.5v6.75m12-6.5v6.75");
}

.w2fp3ub6f {
  cx: 18px;
  cy: 16.75px;
  r: 1.25px;
}

</style>
