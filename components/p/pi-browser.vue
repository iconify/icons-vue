<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="he0znwbih"/><path class="v0qzn-blw"/><path class="c7cvtl_dn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pi-browser" /></template>
<style>
.c7cvtl_dn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.054 14.544v1.326a2.326 2.326 0 0 1-2.326 2.326H15.272a2.326 2.326 0 0 0-2.326 2.326v3.015m7.5-10.037V12m7.63 1.5V12");
}

.he0znwbih {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5c11.879 0 21.5 9.621 21.5 21.5S35.879 45.5 24 45.5S2.5 35.879 2.5 24S12.121 2.5 24 2.5");
}

.v0qzn-blw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.52 20.39c-.23 1.17-.36 2.37-.36 3.61c0 9.86 7.98 17.84 17.84 17.84c6.79 0 12.7-3.79 15.71-9.37M6.52 20.39l-3.46-1.26m40.11 14.6l-3.46-1.26M20.446 36V18.196M28.076 36V18.196");
}

</style>
