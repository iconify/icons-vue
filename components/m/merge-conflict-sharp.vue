<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="x8xz1dbpx"/><circle class="tngq42bwk"/><path class="bcik517_p"/><path class="weuigy23k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:merge-conflict-sharp" /></template>
<style>
.bcik517_p {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 15.75v1.5");
}

.tngq42bwk {
  cx: 12px;
  cy: 17.5px;
  r: 3.75px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.weuigy23k {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 19.25h.01");
}

.x8xz1dbpx {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 2.75v2.5C5.75 8.5 12 8.5 12 11.5m6.25-8.75v2.5C18.25 8.5 12 8.5 12 11.5");
}

</style>
