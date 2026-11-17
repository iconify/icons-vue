<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="wz4bq8w1f"/><path class="hirtlzbtx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:warehouse-duocolor-round" /></template>
<style>
.hirtlzbtx {
  d: path("M12 21H8a4 4 0 0 1-4-4v-6.528a4 4 0 0 1 2.211-3.578l2.944-1.472A4 4 0 0 1 10.945 5h2.11a4 4 0 0 1 1.79.422l2.944 1.472A4 4 0 0 1 20 10.472V17a4 4 0 0 1-4 4z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.wz4bq8w1f {
  stroke-opacity: 0.4;
  d: path("M8 21v-7a2 2 0 0 1 2-2h4a2 2 0 0 1 2 2v7m-8-5h8");
}

</style>
