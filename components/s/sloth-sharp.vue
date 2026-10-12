<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="gsfotvrki"/><circle class="ny11racyo"/><path class="pb732ds_r"/><path class="c7ltdsbtg"/><path class="fxtt7lqiv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sloth-sharp" /></template>
<style>
.c7ltdsbtg {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.25 13.5l-.95-1.9l-1.8.9l-1.833.917L13.25 15l1 1l1.25 1.25l1-1.5l.625-.937z");
}

.fxtt7lqiv {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 13.75h.01m4.99 0h.01M12 17.25h.01");
}

.gsfotvrki {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 4h18.5M6.75 9V4H8m9.25 5V4H16");
}

.ny11racyo {
  cx: 12px;
  cy: 14px;
  r: 7.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pb732ds_r {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m7.75 13.5l.95-1.9l1.8.9l1.833.917L10.75 15l-1 1l-1.25 1.25l-1-1.5l-.625-.937z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
