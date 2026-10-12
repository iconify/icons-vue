<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ecbb2la-d"/><circle class="rdo2hgb7w"/><path class="tp0wa0tss"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rangoli-sharp" /></template>
<style>
.ecbb2la-d {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m12.57 3.57l1.25 1.83l.57.83l.99-.19l2.18-.4l.98-.18l-.18.98l-.4 2.18l-.19.99l.83.57l1.83 1.25l.82.57l-.82.57l-1.83 1.25l-.83.57l.19.99l.4 2.18l.18.98l-.98-.18l-2.18-.4l-.99-.19l-.57.83l-1.25 1.83l-.57.82l-.57-.82l-1.25-1.83l-.57-.83l-.99.19l-2.18.4l-.98.18l.18-.98l.4-2.18l.19-.99l-.83-.57l-1.83-1.25l-.82-.57l.82-.57l1.83-1.25l.83-.57l-.19-.99l-.4-2.18l-.18-.98l.98.18l2.18.4l.99.19l.57-.83l1.25-1.83l.57-.82z");
}

.rdo2hgb7w {
  cx: 12px;
  cy: 12px;
  r: 2.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.tp0wa0tss {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 6.75h.01M12 17.25h.01M6.75 12h.01m10.49 0h.01M8.3 8.3h.01m7.39 0h.01M8.3 15.7h.01m7.39 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
