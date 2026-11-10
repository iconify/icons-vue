<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="pmtwkktcd"/><path class="vd1j6lbib"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:navigation-up-right-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pmtwkktcd {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19.673 3.05C20.034 2.93 20.434 3.02 20.704 3.29C20.974 3.56 21.067 3.96 20.944 4.32L15.461 20.32C15.333 20.69 14.998 20.96 14.606 20.99C14.213 21.03 13.836 20.83 13.643 20.49L9.991 13.98L3.512 10.36C3.168 10.16 2.969 9.79 3.004 9.39C3.04 9 3.303 8.67 3.676 8.54L19.673 3.05Z");
  stroke: none;
}

.vd1j6lbib {
  d: path("M19.997 4L4 9.48L10.725 13.25L14.515 20L19.997 4Z");
}

</style>
