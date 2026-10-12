<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ew_4hibuv"/><path class="cvw-6lmqu"/><path class="n0a8omxqi"/><path class="wl1ltbces"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:salt-pepper-sharp" /></template>
<style>
.cvw-6lmqu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.9 12.75h.01m2.69 0h.01");
}

.ew_4hibuv {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 21.25V12a3.5 3.5 0 0 1 7 0v9.25Z");
}

.n0a8omxqi {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.25 21.25V10a3.5 3.5 0 0 1 7 0v11.25Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.wl1ltbces {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M16.75 10.75h.01");
}

</style>
