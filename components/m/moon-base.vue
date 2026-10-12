<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="y9tr6bcfx"><path class="kkjj_7fin"/><path class="n80yrrvnh"/><circle class="ba76p1n5h"/><path class="a0rzm1pyk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:moon-base" /></template>
<style>
.a0rzm1pyk {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.5 6h.01M10 3.75h.01");
}

.ba76p1n5h {
  cx: 17.75px;
  cy: 6.25px;
  r: 3px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kkjj_7fin {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 20.5a7 7 0 0 1 14 0Z");
}

.n80yrrvnh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 16.5h11.5m-7.25 4v-2.25a1.5 1.5 0 0 1 3 0v2.25m-10.25 0H4.5m14 0h2.75");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
