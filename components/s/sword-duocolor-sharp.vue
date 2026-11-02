<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n7bm7ypnx"/><path class="a-q_tji3x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:sword-duocolor-sharp" /></template>
<style>
.a-q_tji3x {
  d: path("M7 14L18 3h3v3L10 17");
}

.n7bm7ypnx {
  stroke-opacity: 0.4;
  d: path("m5 12l7 7m-4-3l-4 4m-1-1l2 2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
