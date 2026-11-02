<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ryy7bo74d"/><path class="glg82pb0v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:siren-duocolor-round" /></template>
<style>
.glg82pb0v {
  d: path("M8 17v-4a4 4 0 1 1 8 0v4M5 19a2 2 0 0 1 2-2h10a2 2 0 1 1 0 4H7a2 2 0 0 1-2-2m7-6v4");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ryy7bo74d {
  stroke-opacity: 0.4;
  d: path("M12 3v2M4 5l2 2m14-2l-2 2");
}

</style>
