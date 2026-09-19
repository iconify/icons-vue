<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sim83vbhv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:psms" /></template>
<style>
.sim83vbhv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M41.967 35.808A21.5 21.5 0 0 0 45.5 24h0c0-11.874-9.626-21.5-21.5-21.5S2.5 12.126 2.5 24S12.126 45.5 24 45.5a21.5 21.5 0 0 0 11.54-3.36c2.244-1.155 5.735.004 8.366 1.912c-2.03-2.815-3.26-5.842-1.939-8.244");
}

</style>
