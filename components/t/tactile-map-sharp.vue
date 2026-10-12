<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="pywx0pb8w"/><path class="lurr01srd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:tactile-map-sharp" /></template>
<style>
.lurr01srd {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M5.75 9h.01m-.01 3.5h.01m6.24-3h.01M12 13h.01m6.24-3h.01m-.01 3.5h.01");
}

.pywx0pb8w {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.45 4.73L7.8 3.02l.7-.27l.71.23l5.58 1.79l.71.23l.7-.27l4.35-1.71l.7-.27V19l-.7.27l-4.35 1.71l-.7.27l-.71-.23l-5.58-1.79L8.5 19l-.7.27l-4.35 1.71l-.7.27V5zM8.5 3v16m7-14v16");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
