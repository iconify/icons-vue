<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q0ceqjb-f"/><path class="lt90kcqsb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:playtomic" /></template>
<style>
.lt90kcqsb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.375 14.25v19.5a9.75 9.75 0 0 1-9.75 9.75H20.75v-9.75M25.625 24v19.5");
}

.q0ceqjb-f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.75 33.75h-8.125V4.5h13c5.385 0 9.75 4.365 9.75 9.75S31.01 24 25.625 24H20.75zM35.375 24a9.75 9.75 0 0 1-9.75 9.75");
}

</style>
