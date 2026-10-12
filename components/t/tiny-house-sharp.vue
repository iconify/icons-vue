<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="u6-rbuhid"/><path class="m4r17wx7o"/><path class="iwpmudbrd"/><path class="jgj73lbto"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tiny-house-sharp" /></template>
<style>
.iwpmudbrd {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M7 20.25h.01m3.99 0h.01");
}

.jgj73lbto {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19 17h2.25");
}

.m4r17wx7o {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.25 12.5H9.5v2H7.25ZM12 17v-4h2.5v4M3 17h16");
}

.u6-rbuhid {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 16.4v-5.65H3.25l.46-.39l6.83-5.72l.46-.39l.46.39l6.83 5.72l.46.39H17V17H5z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
