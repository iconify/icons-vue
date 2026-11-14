<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="eec9pacda"/><path class="i_3xlgoya"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:poster-snap-frame" /></template>
<style>
.eec9pacda {
  d: path("M17 2.5H4.5a2 2 0 0 0-2 2v15a2 2 0 0 0 2 2H17m0-19L21.5 5v14L17 21.5Z");
}

.i_3xlgoya {
  d: path("M6.75 8a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0ZM6 17.5L9.5 13l2 2.5L13 14");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
