<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="kgu--3b1g"/><path class="lbi_8eh0n"/><path class="eev_56b6j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:portable-toilet-sharp" /></template>
<style>
.eev_56b6j {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M13.5 15.5h.01");
}

.kgu--3b1g {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.25 6.5C4.25 4 7.5 2.75 12 2.75S19.75 4 19.75 6.5Zm1.25 0h13v14.75h-13z");
}

.lbi_8eh0n {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.5 21.25V9.5h7v11.75");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
