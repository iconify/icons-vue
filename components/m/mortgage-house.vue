<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="ayplkabje"/><circle class="gqdwd_bjh"/><path class="iqm3d-b4a"/><path class="bpdd4x3je"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mortgage-house" /></template>
<style>
.ayplkabje {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 18.75v-9.2q0-1 .78-1.62l5.69-4.55q.78-.63 1.56 0l5.69 4.55q.78.62.78 1.62v.7a7 7 0 0 0-7 7v1.5q0 1-1 1h-5.5q-1 0-1-1");
}

.bpdd4x3je {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.6 15.6h.01m3.29 3.3h.01");
}

.gqdwd_bjh {
  cx: 17.25px;
  cy: 17.25px;
  r: 4px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iqm3d-b4a {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19 15.5L15.5 19");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
