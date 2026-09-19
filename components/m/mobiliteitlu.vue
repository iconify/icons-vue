<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vgtx4jb3x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:mobiliteitlu" /></template>
<style>
.vgtx4jb3x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.338 34.98V13.178l3.419.04l9.27 11.708l8.122-11.872l2.169.018l-.047 22.01c-.07.07-20.546 6.824-20.546 6.824C14.421 43.714 8.68 41.305 8.68 35.9V7.125c0-.315.208-1.678 1.562-1.623c0 0 26.137 1.799 29.08 2.226h0");
}

</style>
