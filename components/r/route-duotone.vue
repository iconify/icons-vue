<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="dp5us6qto"/><path class="berwx-x7l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:route-duotone" /></template>
<style>
.berwx-x7l {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M4 18a2 2 0 1 0 4 0a2 2 0 0 0-4 0M16 6H8a2 2 0 0 0-2 2v2a2 2 0 0 0 2 2h8a2 2 0 0 1 2 2v2a2 2 0 0 1-2 2H8m8-12a2 2 0 1 0 4 0a2 2 0 0 0-4 0");
}

.dp5us6qto {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M18 8a2 2 0 1 1-.001-3.999A2 2 0 0 1 18 8M6 20a2 2 0 1 1-.001-3.999A2 2 0 0 1 6 20");
}

.ft5dv1b6b {
  fill: none;
}

</style>
