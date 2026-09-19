<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="bv5_6pbmv"/><path class="u5_5sacyy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:tv-browser-updateplugin" /></template>
<style>
.bv5_6pbmv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.207 24.21h-6.091l-5.167 12.705l-7.898-25.831l-5.167 12.705h-6.09");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.u5_5sacyy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.576 11.573L36.19 14.29l3.016 1.992l-3.607.234l.724 3.542l-2.717-2.385l-1.992 3.017l-.235-3.608l-3.542.724l2.385-2.716l-3.016-1.993l3.607-.234l-.724-3.542l2.717 2.385L34.8 8.69l.235 3.607z");
}

</style>
