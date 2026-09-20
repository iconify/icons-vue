<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zum8rmbvd"/><path class="qjm_enzat"/><path class="bol6i856t"/><path class="jz2wn7nic"/><path class="flc5_hbok"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:presenter-duotone-regular" /></template>
<style>
.bol6i856t {
  d: path("M3 7a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
}

.flc5_hbok {
  d: path("M15 17a3.5 3.5 0 0 1 7 0");
}

.jz2wn7nic {
  d: path("M16.5 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qjm_enzat {
  fill: currentColor;
  d: path("M16.5 10a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.zum8rmbvd {
  fill: currentColor;
  d: path("M3 7a2 2 0 0 1 2 -2h9a2 2 0 0 1 2 2v8a2 2 0 0 1 -2 2H5a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
