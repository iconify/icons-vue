<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yxow7abeb"/><path class="uvugsybla"/><path class="abnm6smsv"/><path class="pty_wsbvs"/><path class="lyaz9_5wc"/><path class="ak_t1bcfw"/><path class="dk412jbfb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:source-citation-duotone-regular" /></template>
<style>
.abnm6smsv {
  d: path("M13 3H6v18h12V8");
}

.ak_t1bcfw {
  d: path("M14 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.dk412jbfb {
  d: path("M8 17h4");
}

.lyaz9_5wc {
  d: path("M8 13h6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pty_wsbvs {
  d: path("M8 9h8");
}

.uvugsybla {
  fill: currentColor;
  d: path("M14 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.yxow7abeb {
  fill: currentColor;
  d: path("M13 3H6v18h12V8");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
