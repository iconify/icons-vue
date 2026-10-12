<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="eboj3lpax"/><path class="uaa9uvfzm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rosary-sharp" /></template>
<style>
.eboj3lpax {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 12.83h.01M7.67 11h.01M7 8.5h.01M7.67 6h.01M9.5 4.17h.01M12 3.5h.01m2.49.67h.01M16.33 6h.01M17 8.5h.01m-.68 2.5h.01m-1.84 1.83h.01");
}

.uaa9uvfzm {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 13.5v2.25m0 0v5.5m-2.25-3.5h4.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
