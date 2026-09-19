<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g6okgmunl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ptt-blue-card" /></template>
<style>
.g6okgmunl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.488 33.95l8.978 9.55V24.4zm29.024-14.083L23.383 35.235V4.5z");
}

</style>
