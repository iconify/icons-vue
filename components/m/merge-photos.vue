<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i8xbsq_5d"/><path class="ly4-pqb6x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:merge-photos" /></template>
<style>
.i8xbsq_5d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.833 20.503v6.826L4.5 33.221V14.779zm8.334.497v6.21L43.5 33.102V14.898z");
}

.ly4-pqb6x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.735 17.946v12.133h-15.47V17.921c5.151.052 10.315.025 15.47.025");
}

</style>
