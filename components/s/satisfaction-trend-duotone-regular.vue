<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="p4xder_gs"/><path class="dd62nsbhm"/><path class="i6i6gyb3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:satisfaction-trend-duotone-regular" /></template>
<style>
.dd62nsbhm {
  d: path("M3 9a2.5 2.5 0 0 1 4 0 2.5 2.5 0 0 1 4 0l-4 4Z");
}

.i6i6gyb3w {
  d: path("m13 19 3 -3 2 2 4 -4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.p4xder_gs {
  fill: currentColor;
  d: path("M3 9a2.5 2.5 0 0 1 4 0 2.5 2.5 0 0 1 4 0l-4 4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
