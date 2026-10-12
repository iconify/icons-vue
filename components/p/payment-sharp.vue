<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="e_qjkubeb"/><circle class="ygphxfbhc"/><path class="yi4q6cbjg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:payment-sharp" /></template>
<style>
.e_qjkubeb {
  d: path("M2.75 3.25h13.5v8H2.75zm0 3h13.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ygphxfbhc {
  cx: 17.25px;
  cy: 17.25px;
  r: 4px;
}

.yi4q6cbjg {
  d: path("m18.38 16.27l-.35-.75h-1.94v.86c0 1.22 2.34.61 2.34 1.78v.83h-2.018l-.292-.73");
}

</style>
