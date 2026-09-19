<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qvogz_z4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:solarman" /></template>
<style>
.qvogz_z4b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.872 4.5S9.99 18.065 9.99 29.49a14.01 14.01 0 0 0 28.018 0c0-8.149-9.187-14.32-9.187-14.32l-8.38 12.677h7.706l-6.314 9.55");
}

</style>
