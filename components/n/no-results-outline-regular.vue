<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="aai5cvb0q"/><path class="g69nh1q2b"/><path class="x6kbyg_lb"/><path class="ury5s7a4p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:no-results-outline-regular" /></template>
<style>
.aai5cvb0q {
  d: path("M4 10a5 5 0 1 0 10 0 5 5 0 1 0 -10 0");
}

.g69nh1q2b {
  d: path("m5.5 13.5 -3 3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ury5s7a4p {
  d: path("m22 12 -5 5");
}

.x6kbyg_lb {
  d: path("m17 12 5 5");
}

</style>
