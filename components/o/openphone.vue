<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y161h-int"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:openphone" /></template>
<style>
.y161h-int {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.293 38.023C37.14 38.023 43.5 31.745 43.5 24S37.14 9.977 29.293 9.977S15.085 16.255 15.085 24s6.36 14.023 14.208 14.023m-14.15-3.519c5.879 0 10.644-4.703 10.644-10.504s-4.765-10.504-10.644-10.504S4.5 18.199 4.5 23.999s4.765 10.505 10.643 10.505");
}

</style>
