<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="sx9-3cb4u"/><path class="q6c4nebpj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:minaret-sharp" /></template>
<style>
.q6c4nebpj {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 19.5v-3");
}

.sx9-3cb4u {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75V4.5m0 0l2.5 1.719V8.5h-5V6.219zm-1.25 4h3V12h1.75v1.75h-.75l.05.5l.65 6.5l.05.5h-7l.05-.5l.65-6.5l.05-.5H8.5V12h1.75V8.5z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
