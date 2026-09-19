<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="y-90c08bv"/><path class="cshlkstwb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:videosummarizer" /></template>
<style>
.cshlkstwb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.34 14.997v11.51l9.966-5.755z");
}

.y-90c08bv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m16.02 8.045l15.764-.076c6.546-.032 11.536 5.853 11.71 12.954c.278 11.424-7.968 16.485-14.287 19.108v-8.13H16.02c-6.79 0-11.52-4.634-11.52-10.978c0-7.722 3.898-12.841 11.52-12.878");
}

</style>
