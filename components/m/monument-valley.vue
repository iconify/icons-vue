<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="v_psb0iau"/><path class="rk7g9prwf"/><path class="jxs_agbws"/><path class="tbxcf_bsm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:monument-valley" /></template>
<style>
.jxs_agbws {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28.299 8.772c-3.565 1.508-4.519 4.546-4.202 8.06m1.871 1.049c0 4.634-8.916 7.728-8.916 10.716s2.916 5.833 8.038 5.833s6.651-2.276 6.651-3.948s-3.443-6.952-3.443-12.528");
}

.rk7g9prwf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.869 9.438a4.705 4.705 0 0 0-1.067 8.338");
}

.tbxcf_bsm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.463 19.792a3.49 3.49 0 0 0 2.994.306m-3.189 14.331v7.648l1.46 1.423m1.317-9.388v6.054l1.286 1.12");
}

.v_psb0iau {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.313 15.78a4.703 4.703 0 0 0-1.62-6.45a5.7 5.7 0 0 0-1.395-.558C26.41 8.235 12.018 4.5 12.018 4.5s10.465 10.854 12.079 12.332a4.708 4.708 0 0 0 7.216-1.051");
}

</style>
