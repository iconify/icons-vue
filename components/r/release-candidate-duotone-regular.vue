<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nwys7tb-b"/><path class="l_resynoa"/><path class="c5icmybsm"/><path class="zhn_01m4j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:release-candidate-duotone-regular" /></template>
<style>
.c5icmybsm {
  d: path("m4 12 6 -6h10v12H10Z");
}

.l_resynoa {
  fill: currentColor;
  d: path("m14 9.5 2.5 2.5 -2.5 2.5 -2.5 -2.5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nwys7tb-b {
  fill: currentColor;
  d: path("m4 12 6 -6h10v12H10Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zhn_01m4j {
  d: path("m14 9.5 2.5 2.5 -2.5 2.5 -2.5 -2.5Z");
}

</style>
