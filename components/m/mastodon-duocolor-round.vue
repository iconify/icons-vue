<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rmboa2b4m"/><path class="ooe9rly_k"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mastodon-duocolor-round" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ooe9rly_k {
  d: path("M8 13V9a2 2 0 1 1 4 0v2m0-2a2 2 0 1 1 4 0v4");
}

.rmboa2b4m {
  stroke-opacity: 0.4;
  d: path("M18.65 15.25C16.83 17.02 12 17 12 17H9c.84 1.61 3.83 2.43 8.69 2.1c-1.94 2.01-13.59 5.26-13.66-7.64L4 10.31c0-3.04.02-4.12 1.35-5.63C7.02 3 12 3 12 3s4.98 0 6.65 1.68C19.98 6.2 20 7.27 20 10.31s-.46 4.07-1.35 4.94");
}

</style>
