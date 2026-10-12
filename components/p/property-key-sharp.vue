<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="sshmwcbfg"/><path class="qgna_dwcr"/><path class="kyk6c_b5e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:property-key-sharp" /></template>
<style>
.kyk6c_b5e {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.75 14h8.5m-5.75 0v2.75M18.25 14v2.75m3-2.75v3");
}

.qgna_dwcr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7.75 13h.01");
}

.sshmwcbfg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 17v-6.25l.78-.62l3.44-2.76l.78-.62l.78.62l3.44 2.76l.78.62V18h-10z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
