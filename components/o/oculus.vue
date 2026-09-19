<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ffiu-bb_a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:oculus" /></template>
<style>
.ffiu-bb_a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.054 36.446H16.946a12.446 12.446 0 0 1 0-24.892h14.108a12.446 12.446 0 1 1 0 24.892m-14.108-16.46a4.013 4.013 0 1 0 0 8.027h14.108a4.013 4.013 0 1 0 0-8.026Z");
}

</style>
