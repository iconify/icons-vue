<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="sghruib9u"/><path class="mz0rerbat"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:shorts-sharp-two-tone" /></template>
<style>
.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.mz0rerbat {
  d: path("M3.998 8V4H19.998V8M3.998 8L2 18.88L9.703 20L12.04 12.23L14.212 20L21.997 18.93L19.998 8M3.998 8H8.998M19.998 8H14.998");
}

.sghruib9u {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19.998 3C20.55 3 20.998 3.45 20.998 4V7.91L22.98 18.75C23.029 19.02 22.966 19.29 22.807 19.52C22.646 19.74 22.403 19.88 22.133 19.92L14.349 20.99C13.853 21.06 13.384 20.75 13.249 20.27L12.005 15.82L10.66 20.29C10.517 20.76 10.049 21.06 9.558 20.99L1.856 19.87C1.587 19.83 1.346 19.68 1.187 19.46C1.029 19.24 0.967 18.97 1.016 18.7L2.998 7.91V4C2.998 3.45 3.446 3 3.998 3H19.998Z");
  stroke: none;
}

</style>
