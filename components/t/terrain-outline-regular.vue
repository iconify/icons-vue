<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qaia1d1wv"/><path class="wt9iv5biz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:terrain-outline-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qaia1d1wv {
  d: path("m2 12 6 -6 3 3 5 -5 5 5");
}

.wt9iv5biz {
  d: path("m2 19 6 -6 3 3 5 -5 5 5");
}

</style>
