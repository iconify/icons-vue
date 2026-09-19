<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m30k_p0at"/><path class="cax6nfboe"/><circle class="ykqhogbnn"/><path class="fkf6ool2u"/><circle class="grz104ycv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pannenhilfe" /></template>
<style>
.cax6nfboe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m31.258 21.274l-2.846-8.565a2.29 2.29 0 0 0-2.172-1.567H11.206a2.29 2.29 0 0 0-2.172 1.567l-2.638 7.938a17.6 17.6 0 0 0-.896 5.54v7.903c0 1.3.583 1.883 1.303 1.883h2.009c.72 0 1.303-.583 1.303-1.303V33h14.34");
}

.fkf6ool2u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.402 27.955c-.22.083-.469.138-.73.138c-1.116 0-2.011-.896-2.011-1.998s.895-1.997 2.01-1.997a1.99 1.99 0 0 1 1.97 1.708m3.739 4.315v-5.406");
}

.grz104ycv {
  cx: 32.38px;
  cy: 33.423px;
  r: 0.75px;
  fill: currentColor;
}

.m30k_p0at {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.38 19.33L22.261 36.858H42.5zM6.396 20.647H31.05");
}

.ykqhogbnn {
  cx: 12.483px;
  cy: 26.1px;
  r: 1.998px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
