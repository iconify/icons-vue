<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dldnhmbjp"/><path class="f-tyqx3kx"/><circle class="ygphxfbhc"/><path class="lugpfbc9h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:time-zone" /></template>
<style>
.dldnhmbjp {
  d: path("M12 21.25A9.25 9.25 0 1 1 21.25 12");
}

.f-tyqx3kx {
  d: path("M12 2.75C9.6 5.25 8.35 8.35 8.35 12S9.6 18.75 12 21.25M2.75 12H12m0-9.25c1.6 1.7 2.7 3.7 3.25 6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lugpfbc9h {
  d: path("M17.25 15.5v1.75l1.25.75");
}

.ygphxfbhc {
  cx: 17.25px;
  cy: 17.25px;
  r: 4px;
}

</style>
