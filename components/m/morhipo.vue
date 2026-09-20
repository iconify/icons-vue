<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yw56i0yze"/><path class="aho2qcbcb"/><circle class="c8rc4nxbn"/><path class="yleqlbcmv"/><path class="i9clfwm2k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:morhipo" /></template>
<style>
.aho2qcbcb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.963 23.676c0-.793.649-1.442 1.441-1.442s1.442.65 1.442 1.442v2.378m9.811-5.766v5.838m0-2.45c0-.793.649-1.442 1.441-1.442s1.442.65 1.442 1.442v2.45m-6.126-2.45c0-.793.649-1.442 1.442-1.442m-1.442 0v3.892");
}

.c8rc4nxbn {
  cx: 29.437px;
  cy: 20.505px;
  r: 0.75px;
  fill: currentColor;
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.yleqlbcmv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.437 22.234v3.892m1.873-1.441c0 .792.648 1.441 1.441 1.441s1.442-.649 1.442-1.441v-.937c0-.793-.649-1.442-1.442-1.442s-1.441.649-1.441 1.441m0-1.513V28m6.169-1.874a1.446 1.446 0 0 1-1.442-1.441v-.937c0-.793.649-1.442 1.442-1.442s1.441.649 1.441 1.442v.937c0 .793-.649 1.441-1.441 1.441");
}

.yw56i0yze {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.122 26.126a1.446 1.446 0 0 1-1.442-1.441v-.937c0-.793.65-1.442 1.442-1.442c.793 0 1.442.649 1.442 1.442v.937c0 .793-.65 1.441-1.442 1.441m-9.042-2.45c0-.793.649-1.442 1.441-1.442s1.442.65 1.442 1.442v2.378m-2.883-3.82v3.892");
}

</style>
