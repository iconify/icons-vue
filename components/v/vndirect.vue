<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q2hjr-pbc"/><path class="bjjcisbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:vndirect" /></template>
<style>
.bjjcisbaz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.56 6.875h8.5c8 0 12.63 7.5 12.63 15l-.03 4.25c-.049 7-4.6 15-12.6 15h-8.75");
}

.q2hjr-pbc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M13.41 35.625v-23.5h5.5c6 0 10.5 4.5 10.5 10.25v3c0 5.5-4.5 10.25-10.5 10.25z");
}

</style>
