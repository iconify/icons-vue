<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="h9256c73q"/><path class="q14_0brox"/><path class="iu0ag9bjl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:suit-sharp" /></template>
<style>
.h9256c73q {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.25 3.25h7l1.27.79l1.46.92l1.27.79l.1 1.5l.8 12l.1 1.5H2.75l.1-1.5l.8-12l.1-1.5l1.27-.79l1.46-.92l1.27-.79z");
}

.iu0ag9bjl {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 17.5h.01");
}

.q14_0brox {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m8 3.75l4 10.75l4-10.75");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
