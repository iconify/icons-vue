<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rsxmkkb6q"/><path class="mbt4yzbhr"/><path class="y_8jdcbuv"/><path class="l4avcpa0j"/><path class="oscmqi7_r"/><path class="z9ittvbis"/><path class="qvtmo6b3b"/><path class="a46bghb1i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:tab-new-duotone-regular" /></template>
<style>
.a46bghb1i {
  d: path("M18 10v6");
}

.l4avcpa0j {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M18 10v6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mbt4yzbhr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 19h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.oscmqi7_r {
  d: path("M2 19V9l2 -2h6l2 2v10");
}

.qvtmo6b3b {
  d: path("M15 13h6");
}

.rsxmkkb6q {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 19V9l2 -2h6l2 2v10");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y_8jdcbuv {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M15 13h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.z9ittvbis {
  d: path("M2 19h20");
}

</style>
