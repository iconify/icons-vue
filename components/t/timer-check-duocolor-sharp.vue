<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="oj7os7b1h"/><path class="ubqfwcbya"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:timer-check-duocolor-sharp" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oj7os7b1h {
  stroke-opacity: 0.4;
  d: path("m8 13l3 3l5-6");
}

.ubqfwcbya {
  d: path("M4 13a8 8 0 1 0 16 0a8 8 0 0 0-16 0m6-10h4m-2 0v2m6 2l2-2");
}

</style>
