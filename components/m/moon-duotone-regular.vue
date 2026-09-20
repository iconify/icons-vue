<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="lwsfc75mg"/><path class="qni2dqmcs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:moon-duotone-regular" /></template>
<style>
.lwsfc75mg {
  fill: currentColor;
  d: path("M18 3a10 10 0 1 0 0 18 12 12 0 0 1 0 -18");
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

.qni2dqmcs {
  d: path("M18 3a10 10 0 1 0 0 18 12 12 0 0 1 0 -18");
}

</style>
