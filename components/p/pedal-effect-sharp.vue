<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="gc9bpdn0n"/><path class="goa6xmsjx"/><circle class="evze8sb2n"/><path class="jsqqbh54i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:pedal-effect-sharp" /></template>
<style>
.evze8sb2n {
  cx: 12px;
  cy: 16.25px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.gc9bpdn0n {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 6.75h14.5v14.5H4.75z");
}

.goa6xmsjx {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 10.25h.01m5.99 0h.01");
}

.jsqqbh54i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 6.75v-4m7 4v-4");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
