<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="xbbnr2b-e"/><circle class="f3bj_2blj"/><path class="vtty5i1nq"/><path class="klobb3s5j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tape-dispenser-sharp" /></template>
<style>
.f3bj_2blj {
  cx: 9.5px;
  cy: 10.25px;
  r: 4px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.klobb3s5j {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m13.26 11.62l7.99 1.88");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.vtty5i1nq {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9.5 10.25h.01");
}

.xbbnr2b-e {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 19.75v1.5h18.5V13.5c0 3.5-3.25 4.75-7.25 4.75H2.75z");
}

</style>
