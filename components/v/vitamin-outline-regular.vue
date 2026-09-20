<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h_n9wsbvm"/><path class="pohupsbfv"/><path class="f99n1fbkg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:vitamin-outline-regular" /></template>
<style>
.f99n1fbkg {
  d: path("M16 7h6");
}

.h_n9wsbvm {
  d: path("m4 13 6 -6a4 4 0 0 1 5 5l-6 6a4 4 0 0 1 -5 -5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pohupsbfv {
  d: path("M19 4v6");
}

</style>
