<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="quhf9pj8o"/><path class="b1b39f6uh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shovel-duocolor" /></template>
<style>
.b1b39f6uh {
  d: path("m11 13l2 2a1.414 1.414 0 0 1 0 2l-1 1H8a2 2 0 0 1-2-2v-4l1-1a1.414 1.414 0 0 1 2 0z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.quhf9pj8o {
  stroke-opacity: 0.4;
  d: path("m11 13l6-6m-2-2l4 4");
}

</style>
