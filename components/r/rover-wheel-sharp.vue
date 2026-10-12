<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="j6xdb3xox"/><circle class="afkgn0o3z"/><path class="pdkbpr4jm"/><path class="lbas3bqos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:rover-wheel-sharp" /></template>
<style>
.afkgn0o3z {
  cx: 10.25px;
  cy: 13.9px;
  r: 3.5px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j6xdb3xox {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m16.08 16.76l1.49 1.49l-2.97 2.97l-1.49-1.49a6.5 6.5 0 0 1-5.72 0L5.9 21.22l-2.97-2.97l1.49-1.49a6.5 6.5 0 0 1 0-5.72L2.93 9.55L5.9 6.58l1.49 1.49a6.5 6.5 0 0 1 5.72 0l1.49-1.49l2.97 2.97l-1.49 1.49a6.5 6.5 0 0 1 0 5.72Z");
}

.lbas3bqos {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M10.25 7.4V4.25H18m0-1.5h3.25V5.5H18z");
}

.pdkbpr4jm {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.25 13.9h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
