<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="n_kp27b4m"/><rect class="ht6jihdba"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:vr-headset" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ht6jihdba {
  width: 12px;
  height: 2.5px;
  x: 6px;
  y: 9.75px;
  rx: 1.25px;
}

.n_kp27b4m {
  d: path("M7 7.25V5.5A1.5 1.5 0 0 1 8.5 4h7A1.5 1.5 0 0 1 17 5.5v1.75m-12 0h14a2 2 0 0 1 2 2V15a2 2 0 0 1-2 2h-3.2a1.5 1.5 0 0 1-1.25-.67l-1.3-1.95a1.5 1.5 0 0 0-2.5 0l-1.3 1.95A1.5 1.5 0 0 1 8.2 17H5a2 2 0 0 1-2-2V9.25a2 2 0 0 1 2-2");
}

</style>
