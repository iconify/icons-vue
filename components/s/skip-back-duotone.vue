<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ij1pfkrsz"/><path class="vo3vzdbab"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:skip-back-duotone" /></template>
<style>
.ij1pfkrsz {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M20 16.994101C20 19.596298 16.91367 20.964488 14.985461 19.217079L8.656973 13.481985C7.781008 12.688156 7.781008 11.311844 8.656973 10.518015L14.985461 4.782921C16.91367 3.035512 20 4.403702 20 7.005899Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.vo3vzdbab {
  d: path("M5 5L5 19");
}

</style>
