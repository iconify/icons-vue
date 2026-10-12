<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="gakk76b9v"/><path class="egp1vpmub"/><path class="cyxhjjb8z"/><path class="jvwyttbgr"/><path class="irqr5zdpt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:money-exchange-sharp" /></template>
<style>
.cyxhjjb8z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.75 13.75h11.5v7H9.75z");
}

.egp1vpmub {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.5 6.75h.01");
}

.gakk76b9v {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.25h11.5v7H2.75z");
}

.irqr5zdpt {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M16.5 4.75h2.75v5.5M17.5 8.5l1.75 1.75L21 8.5M7.5 19.25H4.75v-5.5M3 15.5l1.75-1.75L6.5 15.5");
}

.jvwyttbgr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.5 17.25h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
