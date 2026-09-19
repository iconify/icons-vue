<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="z_1-98bdf"/><path class="oo4k_vbaa"/><circle class="xg7c9pbrd"/><circle class="agx1x11-v"/><circle class="vvrtqubhi"/><circle class="r191kac1u"/></g><path class="da84w3d0t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:so-suc-khoe-dien-tu" /></template>
<style>
.agx1x11-v {
  cx: 36.011px;
  cy: 29.857px;
  r: 1.501px;
}

.da84w3d0t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.092 26.395c3.757-5.313 3.049-13.033-1.643-17.378c-4.764-4.411-11.827-3.676-15.778 1.642q-.376.507-.703 1.055c-2.08-3.423-5.543-5.472-9.247-5.47h-.011l-.001-.003C8.527 6.231 3.509 11.82 3.5 18.723c-.003 2.881.885 5.675 2.515 7.91l1.856 2.432");
}

.oo4k_vbaa {
  d: path("M24.504 41.865c2.756-3.315 3.632-4.875 5.503-11.508c1.933 2.732 2.97 4.99 9.507 1c-4.522 5.418-5.432 7.827-15.01 10.508m-3.002-.501c-1.683-3.93-1.54-7.27-5.504-12.008c.32 2.7-.006 4.78-1.501 6.004c2.348.924 5.483 3.607 7.005 6.004");
}

.r191kac1u {
  cx: 28.506px;
  cy: 20.851px;
  r: 2.001px;
}

.vvrtqubhi {
  cx: 12.996px;
  cy: 31.858px;
  r: 1.501px;
}

.xg7c9pbrd {
  cx: 19px;
  cy: 17.849px;
  r: 2.001px;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.z_1-98bdf {
  d: path("M13.997 17.348c3.034 4.13 5.645 6.26 9.006 5.504c1.59 8.626 1.311 13.4 0 17.512c-.63-3.65-1.93-7.37-4.253-10.352c-3.57-4.583-5.704-8.332-4.753-12.664m10.507 24.517c2.637-5.141 2.499-11.798 1-16.011c8.71-1.173 7.331-5.55 10.007-9.006c.772 3.313-.506 10.297-4.003 15.51");
}

</style>
