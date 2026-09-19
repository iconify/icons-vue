<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nxspsjbjy"/><path class="phetz8wik"/><path class="ephvnsbwx"/><path class="hb3ftlbux"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:team-fight-tactics" /></template>
<style>
.ephvnsbwx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.569 41.471V21.533h-7.386l-2.611-5.829h13.399m3.402 22.335V21.533h7.387l2.61-5.829H23.971");
}

.hb3ftlbux {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.803 30.784c2.439 2.712 3.438 6.458-.714 8.084c-3.69 1.446-10.964.964-25.817-5.575M3.198 22.45c2.83 2.948 10.018 7.033 10.018 7.033m27.587 1.301c2.635.798 3.395 2.427 3.395 2.427");
}

.nxspsjbjy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.14 28.588v5.13l16.831 9.717l4.058-2.343c-2.668-.316-7.46-2.787-7.46-2.787m14.576-1.321l5.658-3.266V14.282L23.971 4.565L7.14 14.282v7.074");
}

.phetz8wik {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.431 33.623C9.711 27.844 5.047 24.296 5.047 20.19c0-2.18 2.093-3.016 2.093-3.016");
}

</style>
