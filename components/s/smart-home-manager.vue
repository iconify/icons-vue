<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dnzsokb3u"/><path class="f-cxtl1ie"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:smart-home-manager" /></template>
<style>
.dnzsokb3u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.09 27.388c7.629.114 13.92 6.406 14.51 14.514M8.09 32.387c4.833.113 8.847 4.179 9.395 9.515M8.09 37.408c2.078.115 3.833 1.96 4.276 4.494M39.71 21.81v17.21a2.547 2.547 0 0 1-2.553 2.554H26.103");
}

.f-cxtl1ie {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 24.6L24 6.098l7.436 7.438V7.978h5.195v10.751L42.5 24.6");
}

</style>
