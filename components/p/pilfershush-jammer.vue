<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dr18h6byf"/><path class="pkrug7bhg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pilfershush-jammer" /></template>
<style>
.dr18h6byf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 4.5a8.503 8.503 0 0 1 8.503 8.503v10.512A8.503 8.503 0 0 1 24 32.017h0a8.503 8.503 0 0 1-8.503-8.502V13.003A8.503 8.503 0 0 1 24 4.5");
}

.pkrug7bhg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.855 26.045a13.387 13.387 0 0 0 26.29 0M24 36.898V43.5m-13.145 0h26.29M38.5 7l-29 34m29 0L9.5 7");
}

</style>
