<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ms0wweiwf"/><path class="zfhlhzb4o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:plane-banking" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ms0wweiwf {
  d: path("m15.041 4.482l.026.749a1.5 1.5 0 0 1-.2.802l-.599 1.039a1.5 1.5 0 0 0 .003 1.506l2.23 3.823a1.29 1.29 0 0 1 .003 1.298a.592.592 0 0 1-.92.134l-2.559-2.42a.89.89 0 0 0-1.38.202l-.218.377a1.5 1.5 0 0 0-.115 1.248l.153.436a.426.426 0 0 1-.615.511l-3.2-1.848a.426.426 0 0 1 .135-.788l.454-.085a1.5 1.5 0 0 0 1.023-.724l.218-.377a.89.89 0 0 0-.516-1.296L5.59 8.062a.592.592 0 0 1-.344-.863a1.29 1.29 0 0 1 1.125-.647l4.426.02a1.5 1.5 0 0 0 1.306-.75l.599-1.039a1.5 1.5 0 0 1 .595-.574l.662-.352a.737.737 0 0 1 1.082.625M3.5 16a11 11 0 0 0 17 0");
}

.zfhlhzb4o {
  d: path("m17.5 16.5l3-.5v3");
}

</style>
