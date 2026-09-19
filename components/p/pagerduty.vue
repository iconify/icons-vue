<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="t_gghtd8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pagerduty" /></template>
<style>
.t_gghtd8g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.558 33.113h5.713V43.5h-5.713zM32.074 6.404C29.007 4.772 26.881 4.5 21.86 4.5h-11.3v23.642h11.253c4.476 0 7.815-.272 10.758-2.225c3.215-2.127 4.872-5.664 4.872-9.744c0-4.427-2.053-7.963-5.367-9.769zm-8.952 16.793h-6.85V9.57l6.454-.05c5.886-.074 8.829 2.003 8.829 6.702c0 5.045-3.636 6.974-8.433 6.974z");
}

</style>
