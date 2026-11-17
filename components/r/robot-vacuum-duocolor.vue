<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="kxq47ab9r"/><path class="hv57c-b0i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:robot-vacuum-duocolor" /></template>
<style>
.hv57c-b0i {
  d: path("M4 8a8.944 8.944 0 1 1 16 8A8.944 8.944 0 0 1 4 8m4 6a4.472 4.472 0 1 1 8 0");
}

.kxq47ab9r {
  stroke-opacity: 0.4;
  d: path("M12 16h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
