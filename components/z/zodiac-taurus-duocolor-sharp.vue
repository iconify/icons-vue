<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="hjw8ozblr"/><path class="k_hy43zrd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:zodiac-taurus-duocolor-sharp" /></template>
<style>
.hjw8ozblr {
  stroke-opacity: 0.4;
  d: path("M6 3a6 6 0 1 0 12 0");
}

.k_hy43zrd {
  d: path("M12 9a6 6 0 1 0 0 12m0 0a6 6 0 1 0 0-12");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
