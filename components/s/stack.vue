<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vbt_swb8k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:stack" /></template>
<style>
.vbt_swb8k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5L8.954 15.105L24 25.944M8.852 17.079L6.805 18.52l15.046 10.84m0 0L24 30.908M8.954 23.366L24 34.206M8.954 27.672L24 38.512M8.954 32.66L24 43.5M8.954 15.105V32.66M24 25.944v4.964M24 4.5l15.046 10.605L24 25.944m15.171-8.849l2.024 1.426L26.149 29.36m0 0L24 30.908m15.046-7.542L24 34.206m15.046-6.534L24 38.512m15.046-5.852L24 43.5m15.046-28.395V32.66M24 25.944v4.964m0 0V43.5");
}

</style>
