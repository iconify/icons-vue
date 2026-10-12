<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="j2n_xvcvo"/><path class="gkixhdctr"/><path class="czlqulb3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:slideshow-sharp" /></template>
<style>
.czlqulb3m {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M15.75 7.75h.01M8.25 20.5h.01m7.49 0h.01m-4.76 0h2");
}

.gkixhdctr {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 14.25L10 10.5l2.5 2.75l1.75-1.75l3.25 2.75");
}

.j2n_xvcvo {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 3.75h18.5v13.5H2.75z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
