<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="d8vl7nsmr"/><path class="kywmzznkm"/><path class="pjw5o-b4z"/><path class="c4ksau0lb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:outer-join-outline-regular" /></template>
<style>
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

</style>
