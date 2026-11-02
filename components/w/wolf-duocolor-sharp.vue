<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="musryfdwh"/><path class="h70oiabvs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:wolf-duocolor-sharp" /></template>
<style>
.h70oiabvs {
  d: path("m15 7l4-4v6l2 2l-2 2l2 2l-5 2l-2 4h-4l-2-4l-5-2l2-2l-2-2l2-2V3l4 4z");
}

.musryfdwh {
  stroke-opacity: 0.4;
  d: path("m9 11l1 1m5-1l-1 1m-2 6h.01");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
