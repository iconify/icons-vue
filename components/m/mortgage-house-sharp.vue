<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="peoliacxi"/><circle class="gqdwd_bjh"/><path class="iqm3d-b4a"/><path class="bpdd4x3je"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:mortgage-house-sharp" /></template>
<style>
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

.peoliacxi {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 18.75V8.55l.78-.62l5.69-4.55l.78-.63l.78.63l5.69 4.55l.78.62v1.7a7 7 0 0 0-7 7v2.5h-7.5z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
