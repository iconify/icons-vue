<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kxp08h6am"/><path class="jph91n2ni"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:overcast-outline-regular" /></template>
<style>
.jph91n2ni {
  d: path("M7 21a3.5 3.5 0 0 1 2 -6 4.5 4.5 0 0 1 8 -1 4.5 4.5 0 0 1 3 7Z");
}

.kxp08h6am {
  d: path("M2 12a3 3 0 0 1 2 -5.5 4 4 0 0 1 7.5 -1A4.5 4.5 0 0 1 15 12Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
