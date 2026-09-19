<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oeswybbaj"/><path class="bwobthbsc"/><path class="blaa8cbpo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:utd-rooms" /></template>
<style>
.blaa8cbpo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.594 26.018c.058 1.54-.644 2.547-1.375 2.266c-.594-.23-1.014-1.223-1.042-2.276c-.027-1.039.282-2.225.903-2.298c.839-.099 1.457.796 1.514 2.308");
}

.bwobthbsc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.245 4.5l21.51.073l-.073 35.781l-3.22.074");
}

.oeswybbaj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m13.249 4.518l18.133 2.57l.007 36.412l-18.144-2.57Z");
}

</style>
