<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uhve_kb3h"/><path class="b18ioelvz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:playing-cards-duocolor-round" /></template>
<style>
.b18ioelvz {
  d: path("M4 11a4 4 0 0 1 4-4h4a4 4 0 0 1 4 4v6a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4Zm4-8h8a4 4 0 0 1 4 4v10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.uhve_kb3h {
  stroke-opacity: 0.4;
  d: path("m10 11l2 3l-2 3l-2-3Z");
}

</style>
