<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="e-dceibbr"/><path class="hptkvpp9b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:robinhood" /></template>
<style>
.e-dceibbr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.848 43.5c1.697-9.276 15.676-27.632 19.498-31.128l-11.7 2.531l-7.046 9.236s.842 4.986 2.546 10.935");
}

.hptkvpp9b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m17.647 14.903l8.346-8.962s7.414-3.242 10.741 0c2.668 2.6.753 7.867.753 7.867c-4.173 4.858-9.236 11.7-12.041 18.54l-12.709 3.518m16.609-23.494l-1.307 14.672m-7.656 9.546l-5.766 1.644");
}

</style>
