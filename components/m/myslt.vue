<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xbs-8wbaw"/><circle class="kqwyhzbdq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:myslt" /></template>
<style>
.kqwyhzbdq {
  cx: 27.137px;
  cy: 27.244px;
  r: 2.692px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.xbs-8wbaw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.878 38.11c5.71-9.788 11.339-16.8 11.339-16.8c.955-1.416 4.548-.247 3.67 2.446a1634 1634 0 0 1-11.339 16.8c-1.481 2.262-5.235-.259-3.67-2.447M7.796 39.166c5.71-9.787 11.34-16.8 11.34-16.8c.955-1.415 4.547-.247 3.669 2.447a1634 1634 0 0 1-11.339 16.8c-1.48 2.261-5.234-.259-3.67-2.447M7.35 22.905c5.71-9.787 11.34-16.8 11.34-16.8c.955-1.415 4.548-.246 3.67 2.447a1634 1634 0 0 1-11.339 16.8c-1.481 2.262-5.235-.259-3.67-2.447");
}

</style>
