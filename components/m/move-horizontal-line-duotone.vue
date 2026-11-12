<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ti-w8z23v"/><path class="ist54rbfb"/><path class="u51xaccpr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:move-horizontal-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ist54rbfb {
  stroke-linejoin: round;
  d: path("M5.99954 7.8584L1.85791 12L5.99954 16.1416");
}

.ti-w8z23v {
  d: path("M22.1422 12.0001L1.85791 12");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.u51xaccpr {
  stroke-linejoin: round;
  d: path("M18.0005 7.8584L22.1422 12L18.0005 16.1416");
}

</style>
