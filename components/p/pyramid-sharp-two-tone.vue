<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="feh6ibd6n"/><path class="o6drkbcuj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:pyramid-sharp-two-tone" /></template>
<style>
.feh6ibd6n {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M1.1702 16.311L11.1702 1.4419C11.356 1.1657 11.6671 1 12 1C12.3329 1 12.644 1.1657 12.8298 1.4419L22.8298 16.311C22.9408 16.476 23 16.6703 23 16.8691C23 17.2441 22.7902 17.5876 22.4565 17.7588L12.4565 22.8897C12.3152 22.9622 12.1588 23 12 23C11.8412 23 11.6848 22.9622 11.5435 22.8897L1.5435 17.7588C1.2098 17.5876 1 17.2441 1 16.8691C1 16.6703 1.0592 16.476 1.1702 16.311Z");
  stroke: none;
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o6drkbcuj {
  d: path("M2 16.8691L12 2L22 16.8691L12 22ZM12 2L12 22");
}

</style>
