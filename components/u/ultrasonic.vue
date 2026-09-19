<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i1zpt-_po"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ultrasonic" /></template>
<style>
.i1zpt-_po {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.504 28.487a3.817 3.817 0 1 1 7.633 0m-.001 7.268a3.817 3.817 0 0 1-7.632 0m0 0v-7.268m7.632 0v7.268m-7.632-7.268v-5.213m-.005.005c0-9.376 8.282-16.977 18.5-16.977s18.5 7.6 18.5 16.977m-.001 5.213a3.817 3.817 0 1 0-7.633 0m.001 7.268a3.817 3.817 0 1 0 7.633 0m-.001 0v-7.268m-7.632 0v7.268m7.632-7.268V23.28");
}

</style>
