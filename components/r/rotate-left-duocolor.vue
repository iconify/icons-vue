<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nwrvp3lao"/><path class="h17lu_b3t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:rotate-left-duocolor" /></template>
<style>
.h17lu_b3t {
  d: path("M19 14v4a2 2 0 0 1-2 2H7a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h1");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nwrvp3lao {
  stroke-opacity: 0.4;
  d: path("M12 6h5a2 2 0 0 1 2 2v2m-4-7l-3 3l3 3");
}

</style>
