<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="arpt66bzw"/><path class="wkrh57b9c"/><path class="mpkuqib0i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:power-up-sharp" /></template>
<style>
.arpt66bzw {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 12.25a9 8.75 0 0 1 18 0v1.5H3z");
}

.mpkuqib0i {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 13.75h7.5v7.5h-7.5V18.5ZM10.5 16v1.75m3-1.75v1.75");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.wkrh57b9c {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 7.5h.01m-4.26 2.75h.01m8.49 0h.01");
}

</style>
