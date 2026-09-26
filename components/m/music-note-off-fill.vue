<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qv26iob9o"/><path class="ndwm85bos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:music-note-off-fill" /></template>
<style>
.ndwm85bos {
  d: path("M9 18L9 9M10.4202 4.7633L21 3L21 15.3431M2 2L22 22");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qv26iob9o {
  fill: currentColor;
  d: path("M10 18C10 20.2091 8.2091 22 6 22C3.7909 22 2 20.2091 2 18C2 15.7909 3.7909 14 6 14C8.2091 14 10 15.7909 10 18ZM19.6465 19.6465C19.1443 19.8736 18.5869 20 18 20C15.7909 20 14 18.2091 14 16C14 15.4131 14.1264 14.8557 14.3535 14.3535Z");
  stroke: none;
}

</style>
