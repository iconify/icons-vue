<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ib-3-ujxl"/><path class="dygl0op_e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:octagon-minus-duotone" /></template>
<style>
.dygl0op_e {
  d: path("M8 12L16 12");
}

.ib-3-ujxl {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14.5645 2C15.4927 2 16.3827 2.369 17.0391 3.0254L20.9746 6.9609C21.631 7.6173 22 8.5073 22 9.4355L22 14.5645C22 15.4927 21.631 16.3827 20.9746 17.0391L17.0391 20.9746C16.3827 21.631 15.4927 22 14.5645 22L9.4355 22C8.5073 22 7.6173 21.631 6.9609 20.9746L3.0254 17.0391C2.369 16.3827 2 15.4927 2 14.5645L2 9.4355C2 8.5073 2.369 7.6173 3.0254 6.9609L6.9609 3.0254C7.6173 2.369 8.5073 2 9.4355 2L14.5645 2Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
