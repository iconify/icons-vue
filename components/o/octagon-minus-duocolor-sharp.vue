<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="q1qzyoe_f"/><path class="qk302m6ft"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:octagon-minus-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.q1qzyoe_f {
  stroke-opacity: 0.4;
  d: path("M8 12h8");
}

.qk302m6ft {
  d: path("M12 3h4l5 5v8l-5 5H8l-5-5V8l5-5z");
}

</style>
