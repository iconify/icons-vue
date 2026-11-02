<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="eyqe9qq5v"/><path class="lyh6rpn2t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:siren-duotone-round" /></template>
<style>
.eyqe9qq5v {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M17 16a3 3 0 1 1 0 6H7a3 3 0 1 1 0-6v-3a5 5 0 0 1 10 0Z");
}

.ft5dv1b6b {
  fill: none;
}

.lyh6rpn2t {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8 17v-4a4 4 0 1 1 8 0v4M5 19a2 2 0 0 1 2-2h10a2 2 0 1 1 0 4H7a2 2 0 0 1-2-2m7-6v4m0-14v2M4 5l2 2m14-2l-2 2");
}

</style>
