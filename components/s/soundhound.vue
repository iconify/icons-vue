<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9_a3lb-p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:soundhound" /></template>
<style>
.i9_a3lb-p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M27.44 4.51a17.2 17.2 0 0 0-5 .56A16.69 16.69 0 0 0 14.77 33L9.1 38.59a16.91 16.91 0 0 0 28.22-7.5A16.68 16.68 0 0 0 33.06 15l5.67-5.6a17 17 0 0 0-11.29-4.89");
}

</style>
