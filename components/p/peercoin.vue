<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q47xjlb_l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:peercoin" /></template>
<style>
.q47xjlb_l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.236 43.5C5.134 41.333 6.635 26.837 7.162 4.515c32.472-.77 43.31 29.179 25.128 37.765c3-15.783-4.366-26.461-16.615-32.386c8.816 6.701 17.047 18.781 11.56 33.606");
}

</style>
