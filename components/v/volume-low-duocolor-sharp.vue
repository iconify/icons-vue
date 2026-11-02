<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zb47z8ole"/><path class="l2emg7y9m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-low-duocolor-sharp" /></template>
<style>
.l2emg7y9m {
  d: path("M11 4v16l-4-4H3V8h4z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.zb47z8ole {
  stroke-opacity: 0.4;
  d: path("M15 8a7.21 7.21 0 0 1 0 8");
}

</style>
