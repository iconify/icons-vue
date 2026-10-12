<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="aygffcbul"/><path class="v6wx0-brw"/><path class="d_lskeb7h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:speed-camera-sharp" /></template>
<style>
.aygffcbul {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 5.75h12.5v7.5H2.75zM15.25 7h3.25v5h-3.25z");
}

.d_lskeb7h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 13.25v8m-3 0h6M20.25 5.5l1-1m0 5h.01m-1.01 4l1 1");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.v6wx0-brw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M6 9.5h.01");
}

</style>
