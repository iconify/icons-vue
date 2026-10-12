<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="ftukv8g4x"/><path class="q5ghrel7z"/><path class="d6fbly8nu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:photo-spot-sharp" /></template>
<style>
.d6fbly8nu {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M17.75 7.25h.01");
}

.ftukv8g4x {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 11.75H6l.75-1.5h2l.75 1.5h3.25v9.5h-10v-9.5z");
}

.q5ghrel7z {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 14.75a1.75 1.75 0 1 0 0 3.5a1.75 1.75 0 1 0 0-3.5Zm10-2.25c-2-1.75-3.5-3.5-3.5-5.25a3.5 3.5 0 0 1 7 0c0 1.75-1.5 3.5-3.5 5.25Z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
