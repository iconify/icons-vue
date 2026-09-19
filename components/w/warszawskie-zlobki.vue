<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="my-fu9ghc"/><path class="tvg_6v5dn"/><path class="n9nopbb9i"/><circle class="c73_a_bhn"/><circle class="kyq20dbyj"/><circle class="ld6jeub5f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:warszawskie-zlobki" /></template>
<style>
.c73_a_bhn {
  cx: 23.343px;
  cy: 16.571px;
  r: 1.631px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.kyq20dbyj {
  cx: 13.242px;
  cy: 25.857px;
  r: 1.517px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ld6jeub5f {
  cx: 35.392px;
  cy: 22.324px;
  r: 1.427px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.my-fu9ghc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.758 22.052c1.087-2.355 11.415-15.22 14.676-15.22s14.223 10.102 15.672 11.959M28.779 20.15c1.812 2.265 5.617 9.739 11.188 2.174M32.13 36.955c.907-5.164 1.631-7.61 3.488-7.61s4.122 2.899 5.889 5.934m-12.094-1.676c.272-3.08-1.555-8.335-4.243-8.335s-3.367 7.202-4.001 9.784");
}

.n9nopbb9i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 41.167c4.394-1.132 26.544-4.53 39-.453M13.242 29.571a28 28 0 0 1-.996 3.171m11.686-12.275c.317 1.223 1.042 4.801 1.042 4.801m10.418.362a33 33 0 0 1 0 3.732");
}

.tvg_6v5dn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.911 15.937c1.63 1.63 5.164 5.345 7.021 4.53s4.349-4.937 4.847-6.522M8.305 25.857c1.223 1.223 3.352 3.76 4.937 3.714s6.523-5.48 6.523-5.48m-13 13.407c1.268-2.174 3.805-4.982 5.48-4.756s3.76 6.387 4.123 8.425");
}

</style>
