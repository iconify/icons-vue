<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="rdbnc-9_h"/><path class="schkgihqh"/><path class="bdg-v1bjo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:trophy-party-sharp" /></template>
<style>
.bdg-v1bjo {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3.5 9.25h.01m16.99 0h.01");
}

.rdbnc-9_h {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 4h8v4.75a4 4 0 0 1-8 0Z");
}

.schkgihqh {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 6H4.5v3.5H8M16 6h3.5v3.5H16m-4 3.25V17m-4 0h8v4.25H8zM3 3.5l1.5 1m16.5-1l-1.5 1M3 14.5l1.75-.75M21 14.5l-1.75-.75");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
