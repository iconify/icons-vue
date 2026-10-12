<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="thk4_ebcr"/><path class="mfv9vj9km"/><path class="k1xkp0ssi"/><circle class="y520bgbjq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:prayer-wheel-sharp" /></template>
<style>
.k1xkp0ssi {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.25 8.5h3.25v4.75");
}

.mfv9vj9km {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 9.9h.01");
}

.thk4_ebcr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 5.25v-2.5m0 11.75v6.75m-4.25-16h8.5v9.25h-8.5zm0 2.5h8.5M7.75 12h8.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.y520bgbjq {
  cx: 19.5px;
  cy: 14.5px;
  r: 1.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
