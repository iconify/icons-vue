<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cnqels9ou"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mhpb" /></template>
<style>
.cnqels9ou {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.903 36.46c16.417 0 21.69-23.475 21.69-30.96h12.503c0 12.759-8.76 37-34.193 37z");
}

</style>
