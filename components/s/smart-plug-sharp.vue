<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="c39u3vblq"/><circle class="d5k02u8qy"/><path class="rrqyg0vzr"/><path class="oa_7729iy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:smart-plug-sharp" /></template>
<style>
.c39u3vblq {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 7.75h15.5v11.5H4.25z");
}

.d5k02u8qy {
  cx: 12px;
  cy: 13.5px;
  r: 3.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.oa_7729iy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 19.25v2m5-2v2m-5.75-17a4.5 4.5 0 0 1 6.5 0");
}

.rrqyg0vzr {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 13.5h.01m2.99 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
