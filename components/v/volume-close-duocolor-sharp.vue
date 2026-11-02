<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="eiuvhjh8d"/><path class="l2emg7y9m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:volume-close-duocolor-sharp" /></template>
<style>
.eiuvhjh8d {
  stroke-opacity: 0.4;
  d: path("m15 9l6 6m0-6l-6 6");
}

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

</style>
