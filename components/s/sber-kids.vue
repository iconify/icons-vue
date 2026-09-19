<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="iaf1nxqhn"/><path class="lykjsgq5l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sber-kids" /></template>
<style>
.iaf1nxqhn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.405 21.988a21.499 21.499 0 1 1-8.95-15.513");
}

.lykjsgq5l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.042 21.39L24 26.682l18.28-13.998");
}

</style>
