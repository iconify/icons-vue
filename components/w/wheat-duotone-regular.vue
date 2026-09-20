<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="n592ufonn"/><path class="nco06-bkq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:wheat-duotone-regular" /></template>
<style>
.n592ufonn {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 21V4m0 4L7 3m5 5 5 -5m-5 10L7 8m5 5 5 -5m-5 10 -5 -5m5 5 5 -5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nco06-bkq {
  d: path("M12 21V4m0 4L7 3m5 5 5 -5m-5 10L7 8m5 5 5 -5m-5 10 -5 -5m5 5 5 -5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
