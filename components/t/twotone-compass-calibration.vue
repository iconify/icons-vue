<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ybou035jp"/><circle class="ygj803pro"/><path class="mij_oqbni"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-compass-calibration" /></template>
<style>
.mij_oqbni {
  fill: currentColor;
  d: path("M17 17c0-2.76-2.24-5-5-5s-5 2.24-5 5s2.24 5 5 5s5-2.24 5-5m-8 0c0-1.65 1.35-3 3-3s3 1.35 3 3s-1.35 3-3 3s-3-1.35-3-3M2 7.15l5 5a7.06 7.06 0 0 1 10-.01l5-5C19.44 4.59 15.9 3 12 3S4.56 4.59 2 7.15m14.84 2.32c-1.44-.91-3.1-1.4-4.84-1.4s-3.41.49-4.85 1.41L4.94 7.26C6.99 5.79 9.44 5 12 5s5 .79 7.05 2.26z");
}

.ybou035jp {
  fill: currentColor;
  d: path("m4.94 7.26l2.21 2.21A9.05 9.05 0 0 1 12 8.07c1.74 0 3.41.49 4.84 1.4l2.21-2.21A12.04 12.04 0 0 0 12 5c-2.56 0-5.01.79-7.06 2.26");
  opacity: var(--svg-opacity--0-3, 0.3);
}

.ygj803pro {
  cx: 12px;
  cy: 17px;
  r: 3px;
  fill: currentColor;
  opacity: var(--svg-opacity--0-3, 0.3);
}

</style>
