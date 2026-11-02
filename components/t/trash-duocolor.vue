<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="c2h4tcc3x"/><path class="f12n-_blv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:trash-duocolor" /></template>
<style>
.c2h4tcc3x {
  stroke-opacity: 0.4;
  d: path("M4 6h16M8 6V5a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v1");
}

.f12n-_blv {
  d: path("M6 6v13a2 2 0 0 0 2 2h8a2 2 0 0 0 2-2V6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
