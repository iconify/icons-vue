<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="z-pzo91gc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:plainapp" /></template>
<style>
.z-pzo91gc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 29.6a7.4 7.4 0 0 1 14.8-.006v.006a7.4 7.4 0 0 1-14.8.002zm20.3 8.3a4.65 4.65 0 1 1 9.3 0a4.65 4.65 0 0 1-9.3 0m-5.5-21.3c0-6.13 4.97-11.1 11.1-11.1s11.1 4.97 11.1 11.1s-4.97 11.1-11.1 11.1s-11.1-4.97-11.1-11.1");
}

</style>
