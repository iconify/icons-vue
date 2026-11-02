<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uiw7oy0ik"/><path class="u_ijsj09x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:tv-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.u_ijsj09x {
  d: path("M3 8h18v12H3Z");
}

.uiw7oy0ik {
  stroke-opacity: 0.4;
  d: path("m8 4l4 4m4-4l-4 4");
}

</style>
