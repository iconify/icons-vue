<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="fiz17333c"/><path class="suwtw2s3j"/><path class="r9vjtzb0z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:white-dwarf-sharp" /></template>
<style>
.fiz17333c {
  cx: 12px;
  cy: 12px;
  r: 2.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.r9vjtzb0z {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14.63 3.92h.01M18.88 7h.01m1.61 5h.01m-1.63 5h.01m-4.26 3.08h.01m-5.27 0h.01M5.12 17h.01M3.5 12h.01m1.61-5h.01m4.24-3.08h.01");
}

.suwtw2s3j {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6.25v1.5m0 8.5v1.5M6.25 12h1.5m8.5 0h1.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
