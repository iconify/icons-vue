<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="evdnq-b_e"/><circle class="ny11racyo"/><path class="wx7kv_bio"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:powder-puff-sharp" /></template>
<style>
.evdnq-b_e {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 7.65c0-3.15 1.5-4.9 3.5-4.9s3.5 1.75 3.5 4.9");
}

.ny11racyo {
  cx: 12px;
  cy: 14px;
  r: 7.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.wx7kv_bio {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 13.5h.01M13 12h.01m1.74 4.25h.01M10.5 17.5h.01");
}

</style>
