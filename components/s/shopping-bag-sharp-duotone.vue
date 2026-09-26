<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="vecvimbom"/><path class="fd5vhobon"/><path class="ik9h6uvfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shopping-bag-sharp-duotone" /></template>
<style>
.fd5vhobon {
  fill: currentColor;
  d: path("M20.5 6L20.8 6.4C20.9298 6.5731 21 6.7836 21 7L21 8L3 8L3 7C3 6.7836 3.0702 6.5731 3.2 6.4L3.5 6Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ik9h6uvfy {
  d: path("M15 10L15 11C15 12.6569 13.6569 14 12 14C10.3431 14 9 12.6569 9 11L9 10");
}

.vecvimbom {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7 2L16.9999 2C17.3147 2 17.611 2.1482 17.7999 2.4L20.8 6.4C20.9298 6.5731 21 6.7836 21 7L21 21C21 21.5523 20.5523 22 20 22L4 22C3.4477 22 3 21.5523 3 21L3 7C3 6.7836 3.0702 6.5731 3.2 6.4L6.2 2.4C6.3889 2.1482 6.6852 2 7 2Z");
  stroke: none;
}

</style>
