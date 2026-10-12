<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ymwbp-blf"/><path class="vf-1rhbls"/><path class="oli-nabxh"/><path class="lbt0ceboz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sheep-sharp" /></template>
<style>
.lbt0ceboz {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M18.5 10.25h.01");
}

.oli-nabxh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16 9.25l-1.6.4l-.9 1.35");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vf-1rhbls {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.38 7.94a2.25 3.25-30 1 1 3.24 5.62a2.25 3.25-30 1 1-3.24-5.62Z");
}

.ymwbp-blf {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 6.75a2 2 0 0 1 3.38.86l2.393-.127l-.303 2.377l1.344 1.39l-1.344 1.39l.303 2.377l-2.393-.127a2 2 0 0 1-3.38.86a2 2 0 0 1-3.38-.86l-2.393.127l.303-2.377l-1.344-1.39L3.78 9.86l-.303-2.377l2.393.127a2 2 0 0 1 3.38-.86Zm-2.5 9.75v3.25m5-3.25v3.25");
}

</style>
