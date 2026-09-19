<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="n54t3tb8f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:sunlight" /></template>
<style>
.n54t3tb8f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.34 24s.66-1.701.66-3.8c0-6.251-5.149-11.4-11.4-11.4H16.4C10.149 8.8 5 13.949 5 20.2s5.149 11.4 11.4 11.4h15.2a3.8 3.8 0 0 0 3.8-3.8c0-2.144-1.656-3.8-3.8-3.8H16.4a3.8 3.8 0 1 1 0-7.6h15.2c6.251 0 11.4 5.149 11.4 11.4s-5.149 11.4-11.4 11.4H16.4C10.149 39.2 5 34.051 5 27.8c0-2.099.66-3.8.66-3.8");
}

</style>
