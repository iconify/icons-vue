<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="aebqjzhul"/><path class="q1pt0ndzm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:unstoppable" /></template>
<style>
.aebqjzhul {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.905 23.711a10.095 10.095 0 0 0 20.19 0l-.001-18.694a21.5 21.5 0 1 1-20.188 0z");
}

.q1pt0ndzm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.7 5.017v19.231a1.7 1.7 0 0 1-3.4 0V5.017");
}

</style>
