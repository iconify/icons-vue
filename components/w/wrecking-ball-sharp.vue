<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="bnz2s1bbv"/><circle class="pv111ubgt"/><path class="s2cyppihi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:wrecking-ball-sharp" /></template>
<style>
.bnz2s1bbv {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 17.25h11.5v4H2.75zm1.5-5h8v5h-8zm5.75 0l8.5-9.5m0 0v8.75");
}

.pv111ubgt {
  cx: 18.5px;
  cy: 14px;
  r: 2.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s2cyppihi {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.25 19.25h.01m6.49 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
