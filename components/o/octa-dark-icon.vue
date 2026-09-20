<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="suv_k099d"/><path class="ctnnjtb-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:octa-dark-icon" /></template>
<style>
.ctnnjtb-h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.663 5.5H16.337L5.5 16.337v15.326L16.337 42.5h15.326L42.5 31.663V16.337z");
}

.suv_k099d {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.294 24a5.25 5.25 0 1 0 0 10.5h3.412a5.25 5.25 0 1 0 0-10.5m0 0a5.25 5.25 0 1 0 0-10.5h-3.412a5.25 5.25 0 1 0 0 10.5m0 0h3.412");
}

</style>
