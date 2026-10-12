<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="c6vt1lbds"/><path class="xy2srvbyo"/><path class="v73-mmb8l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:petri-dish-sharp" /></template>
<style>
.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.v73-mmb8l {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10 10h.01m4.24 1.25h.01M11.5 14.5h.01");
}

.xy2srvbyo {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 5.25a6.75 6.75 0 1 1 0 13.5a6.75 6.75 0 1 1 0-13.5");
}

</style>
