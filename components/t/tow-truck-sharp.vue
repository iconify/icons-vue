<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="y7c056bro"/><path class="x20sm0kag"/><circle class="r_0b548wt"/><path class="ox2ue_b-w"/><circle class="hha4cxblz"/><path class="l0haxibzw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tow-truck-sharp" /></template>
<style>
.hha4cxblz {
  cx: 17px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l0haxibzw {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17 19h.01");
}

.ox2ue_b-w {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 19h.01");
}

.r_0b548wt {
  cx: 7px;
  cy: 19px;
  r: 2.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.x20sm0kag {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.25 8v3.5h5m-7.5-1.75L5.5 4v3.5m0 0v1a1.1 1.1 0 1 1-2.2 0");
}

.y7c056bro {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 13v-1h10V8h4.955l.445.67l2.1 3.08l.25.368v4.632H2.75v-1Z");
}

</style>
