<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="izar1kb8m"/><path class="tq_7myb4n"/><path class="w3ptzmp9a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:network-switch-sharp" /></template>
<style>
.izar1kb8m {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 12.75h18.5v8.5H2.75zM6.5 17h2m2.5 0h2");
}

.tq_7myb4n {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.25 17h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.w3ptzmp9a {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.5 4.5h15m-1.75-1.75L19.5 4.5l-1.75 1.75m1.75 2.5h-15M6.25 7L4.5 8.75l1.75 1.75");
}

</style>
