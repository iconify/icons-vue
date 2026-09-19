<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="rqdy_8xcz"/><path class="k7o5vnbzg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:t-mobile-play" /></template>
<style>
.k7o5vnbzg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.849 16.303L18.84 9.369v13.868z");
}

.rqdy_8xcz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.54 4.5H10.658v39h8.21V28.105h6.672c6.518 0 11.802-5.284 11.802-11.802S32.058 4.5 25.54 4.5");
}

</style>
