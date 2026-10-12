<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="bgws34b3x"/><path class="e8izmkbix"/><path class="zry7r2bey"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:skyscraper-sharp" /></template>
<style>
.bgws34b3x {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 20.5v-9h1.75V5h6.5v6.5H17v9.75H7z");
}

.e8izmkbix {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M10.5 7.75h.01m2.99 0h.01M10.5 14h.01m2.99 0h.01m-3.01 2.75h.01m2.99 0h.01M10.5 19.5h.01m2.99 0h.01");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

.zry7r2bey {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 4.25v-1.5");
}

</style>
