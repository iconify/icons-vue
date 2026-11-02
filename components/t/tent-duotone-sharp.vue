<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="fhnj2iv1j"/><path class="blyjujmyc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tent-duotone-sharp" /></template>
<style>
.blyjujmyc {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M14 3L5 21m5-18l9 18M3 21h18m-11 0l2-5l2 5");
}

.fhnj2iv1j {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M19.894 20.553A1 1 0 0 1 19 22H5a1 1 0 0 1-.894-1.447l7-14a.998.998 0 0 1 1.788 0Z");
}

.ft5dv1b6b {
  fill: none;
}

</style>
