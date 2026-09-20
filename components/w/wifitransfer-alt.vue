<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="k26kjyuzd"/><path class="d87nawb6a"/><path class="umku2khpi"/><path class="qv_0cachz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wifitransfer-alt" /></template>
<style>
.d87nawb6a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.675 7.996a15.17 15.17 0 0 0-19.393.014M36.51 43.5H11.49a.715.715 0 0 1-.714-.715V17.767c0-.395.32-.715.715-.715h22.637l3.096 3.096v22.637c0 .395-.32.715-.715.715");
}

.k26kjyuzd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.84 13.818a7.575 7.575 0 0 0-9.673-.024v.024m12.181-3.05a11.535 11.535 0 0 0-14.695 0");
}

.qv_0cachz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M26.474 18.809h3.183v4.349h-3.183zM16.277 32.838h15.446m0 3.514H16.277m0 3.514h15.446");
}

.umku2khpi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.993 29.204h20.015V43.5H13.993zm4.729-12.152h13.581v7.863H18.722z");
}

</style>
