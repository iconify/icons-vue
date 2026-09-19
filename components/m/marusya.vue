<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fc4d5xx_j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:marusya" /></template>
<style>
.fc4d5xx_j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.543 39.085C10.63 35.869 8.871 33.009 8.871 24s1.758-11.87 4.672-15.085S20.81 4.5 24 4.5s7.543 1.2 10.457 4.415c2.914 3.216 4.672 6.076 4.672 15.085s-1.758 11.87-4.672 15.085S27.19 43.5 24 43.5s-7.543-1.2-10.457-4.415");
}

</style>
