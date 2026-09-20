<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="s686wbgyz"/><path class="bg6_tvgoh"/><path class="d8vl7nsmr"/><path class="kywmzznkm"/><path class="pjw5o-b4z"/><path class="c4ksau0lb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:outer-join-duotone-regular" /></template>
<style>
.bg6_tvgoh {
  fill: currentColor;
  d: path("M11 12a5.5 5.5 0 1 0 11 0 5.5 5.5 0 1 0 -11 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.c4ksau0lb {
  d: path("M14 3h5");
}

.d8vl7nsmr {
  d: path("M2 12a5.5 5.5 0 1 0 11 0 5.5 5.5 0 1 0 -11 0");
}

.kywmzznkm {
  d: path("M11 12a5.5 5.5 0 1 0 11 0 5.5 5.5 0 1 0 -11 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pjw5o-b4z {
  d: path("M5 3h5");
}

.s686wbgyz {
  fill: currentColor;
  d: path("M2 12a5.5 5.5 0 1 0 11 0 5.5 5.5 0 1 0 -11 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
