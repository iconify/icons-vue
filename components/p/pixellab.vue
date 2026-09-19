<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="a8_d1ekuf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:pixellab" /></template>
<style>
.a8_d1ekuf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.46 43.5v-39m7.74 39v-39m0 23.4h7.64a11.7 11.7 0 0 0 0-23.4H10.46");
}

</style>
