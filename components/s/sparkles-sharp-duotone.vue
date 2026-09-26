<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="dayvb9akf"/><path class="sxfavlbce"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:sparkles-sharp-duotone" /></template>
<style>
.dayvb9akf {
  fill: currentColor;
  d: path("M15.9028 8.4328L17.7302 12.2698L21.5672 14.0972C21.9154 14.263 22.1372 14.6143 22.1372 15C22.1372 15.3857 21.9154 15.737 21.5672 15.9028L17.7302 17.7302L15.9028 21.5672C15.737 21.9154 15.3857 22.1372 15 22.1372C14.6143 22.1372 14.263 21.9154 14.0972 21.5672L12.2698 17.7302L8.4328 15.9028C8.0846 15.737 7.8628 15.3857 7.8628 15C7.8628 14.6143 8.0846 14.263 8.4328 14.0972L12.2698 12.2698L14.0972 8.4328C14.263 8.0846 14.6143 7.8628 15 7.8628C15.3857 7.8628 15.737 8.0846 15.9028 8.4328Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.sxfavlbce {
  stroke-opacity: 0.4;
  d: path("M6.25 2.8628L7.4521 5.0479L9.6372 6.25L7.4521 7.4521L6.25 9.6372L5.0479 7.4521L2.8628 6.25L5.0479 5.0479L6.25 2.8628Z");
}

</style>
