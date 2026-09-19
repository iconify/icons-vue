<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<circle class="kxqi7cc3j"/><path class="jm60gobdy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:stopwatch" /></template>
<style>
.jm60gobdy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M22.033 4.5h6.83v4.504h-6.83zm3.415 24.604v-13.72m-1.334-3.888V9.008m2.668 2.488V9.008M6.517 16.857l2.34-3.452l2.849 1.932l-2.34 3.451zm4.019.205l1.777 1.206");
}

.kxqi7cc3j {
  cx: 25.448px;
  cy: 27.465px;
  r: 16.035px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
