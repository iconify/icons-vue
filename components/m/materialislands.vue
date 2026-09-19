<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i00fn115b"/><path class="kt9bbdckf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:materialislands" /></template>
<style>
.i00fn115b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.45 30.24L24 28.18h0l-13.45 2.06L24 4.5z");
}

.kt9bbdckf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.55 30.24L24 28.18h0l13.45 2.06L24 43.5zM24 4.5v39");
}

</style>
