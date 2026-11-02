<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="t2rg7acaq"/><path class="im48wz0-s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:remove-formatting-duocolor-sharp" /></template>
<style>
.im48wz0-s {
  d: path("M3 5h10M8 5v14");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.t2rg7acaq {
  stroke-opacity: 0.4;
  d: path("m15 13l6 6m0-6l-6 6");
}

</style>
