<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="kzxgoablr"/><path class="j1ysqbcqi"/><path class="yg-xhpbdd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:sneeze-sharp" /></template>
<style>
.j1ysqbcqi {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6.25 9.25l1.5 1l-1.5 1m5.5-2l-1.5 1l1.5 1m-4.25 3h3");
}

.kzxgoablr {
  cx: 9px;
  cy: 12px;
  r: 6.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.yg-xhpbdd {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.75 12h.01m2.49-2.75h.01m.24 4.25h.01M18 15.75h.01M18 8.25h.01");
}

</style>
