<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i6-rxobio"/><path class="v1vhinbbe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ns" /></template>
<style>
.i6-rxobio {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 24h15.39l7.5 7.7h8.6L43.5 24l-7.51-7.7");
}

.v1vhinbbe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M43.5 24H30.39l-7.5-7.7H12.01L4.5 24l7.51 7.7");
}

</style>
