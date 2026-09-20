<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="dejb-0bmi"/><path class="pcs1o4b0q"/><path class="gkj6vbuly"/><path class="ui32hib9b"/><path class="zor2con9h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:whiteboard-duotone-regular" /></template>
<style>
.dejb-0bmi {
  fill: currentColor;
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.gkj6vbuly {
  d: path("M2 5a2 2 0 0 1 2 -2h16a2 2 0 0 1 2 2v10a2 2 0 0 1 -2 2H4a2 2 0 0 1 -2 -2Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pcs1o4b0q {
  fill: currentColor;
  d: path("m8 12 6 -6 2 2 -6 6Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.ui32hib9b {
  d: path("M5 20h14");
}

.zor2con9h {
  d: path("m8 12 6 -6 2 2 -6 6Z");
}

</style>
