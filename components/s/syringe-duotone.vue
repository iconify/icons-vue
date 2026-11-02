<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="q5jk1vbkq"/><path class="fsmmrx1br"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:syringe-duotone" /></template>
<style>
.fsmmrx1br {
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m13 7l-6 6a1.414 1.414 0 0 0 0 2l2 2a1.414 1.414 0 0 0 2 0l6-6m-5-5l6 6M8 16l-4 4m5-9l4 4m2-6l3-3m-2-2l4 4");
}

.ft5dv1b6b {
  fill: none;
}

.q5jk1vbkq {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("M13.707 14.293a1 1 0 0 1 0 1.414l-2 2a2.414 2.414 0 0 1-3.414 0l-2-2a2.414 2.414 0 0 1 0-3.414l2-2a1 1 0 0 1 1.414 0Z");
}

</style>
