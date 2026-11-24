<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="pane80bkq"/><path class="v4-7nlbro"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:package-close-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pane80bkq {
  stroke-opacity: 0.4;
  d: path("m10 12l4 4m0-4l-4 4");
}

.v4-7nlbro {
  d: path("M5 6c.613-1.226 1.774-2 3-2h8c1.226 0 2.387.774 3 2l1 2v8a4 4 0 0 1-4 4H8a4 4 0 0 1-4-4V8zM4 8h16");
}

</style>
