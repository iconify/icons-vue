<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="nca7pq6lm"/><path class="qcx0_7byx"/><path class="dwj8i8b7i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:social-event-outline-regular" /></template>
<style>
.dwj8i8b7i {
  d: path("M6 10c1 2 3 2 4 0 1 2 3 2 4 0 1 2 3 2 4 0");
}

.nca7pq6lm {
  d: path("m4 10 8 -8 8 8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qcx0_7byx {
  d: path("M6 10v10h12V10");
}

</style>
