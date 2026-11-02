<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lz692cbkn"/><path class="not0lxbjm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:test-tube-duocolor" /></template>
<style>
.lz692cbkn {
  stroke-opacity: 0.4;
  d: path("M9 12h6");
}

.not0lxbjm {
  d: path("M9 3v15a3 3 0 0 0 6 0V3M7 3h10");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
