<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="i014pri_f"/><path class="r7m2x7j5v"/><path class="wddr6xbrp"/><path class="coe0-zjah"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:token-duotone-regular" /></template>
<style>
.coe0-zjah {
  d: path("M15.5 14H19a3 3 0 0 1 3 3 3 3 0 0 1 -3 3h-7a3 3 0 0 1 -3 -3 3 3 0 0 1 3 -3Z");
}

.i014pri_f {
  fill: currentColor;
  d: path("M8.5 4H12a3 3 0 0 1 3 3 3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3 3 3 0 0 1 3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.r7m2x7j5v {
  fill: currentColor;
  d: path("M15.5 14H19a3 3 0 0 1 3 3 3 3 0 0 1 -3 3h-7a3 3 0 0 1 -3 -3 3 3 0 0 1 3 -3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.wddr6xbrp {
  d: path("M8.5 4H12a3 3 0 0 1 3 3 3 3 0 0 1 -3 3H5a3 3 0 0 1 -3 -3 3 3 0 0 1 3 -3Z");
}

</style>
