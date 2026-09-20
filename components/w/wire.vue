<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y1q9zrb7j"/><path class="xqrxh_b7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:wire" /></template>
<style>
.xqrxh_b7u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 9.55V28.7a11.63 11.63 0 0 1-11.63 11.63A11.63 11.63 0 0 1 20.24 28.7V11.42A3.77 3.77 0 0 1 24 7.66");
}

.y1q9zrb7j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 9.55V28.7a11.63 11.63 0 0 0 11.63 11.63A11.63 11.63 0 0 0 27.76 28.7V11.42A3.77 3.77 0 0 0 24 7.66");
}

</style>
