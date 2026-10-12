<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><circle class="c6vt1lbds"/><path class="o3_6fm7wc"/><path class="fzu4a77bs"/><path class="kvo-pacvp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:no-skating-sharp" /></template>
<style>
.c6vt1lbds {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.fzu4a77bs {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M9 15h.01M15 15h.01");
}

.kvo-pacvp {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.5 5.5l13 13");
}

.o3_6fm7wc {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m6 11.5l.625 1.25h10.75L18 11.5");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
