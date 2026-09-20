<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="fq7shjbor"/><path class="mzp9zz-op"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:origami-outline-regular" /></template>
<style>
.fq7shjbor {
  d: path("M3 14h18c-1 3 -4 6 -9 6s-8 -3 -9 -6");
}

.mzp9zz-op {
  d: path("M11 11V3l8 8Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
