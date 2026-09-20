<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="yt7qsrz-s"/><path class="esz0ytbwn"/><path class="x18f3082o"/><path class="hj3gyvb8c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:price-up-duotone-regular" /></template>
<style>
.esz0ytbwn {
  d: path("M8 17a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
}

.hj3gyvb8c {
  d: path("M9.5 6 12 3.5 14.5 6");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.x18f3082o {
  d: path("M12 3.5V10");
}

.yt7qsrz-s {
  fill: currentColor;
  d: path("M8 17a4 4 0 1 0 8 0 4 4 0 1 0 -8 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
