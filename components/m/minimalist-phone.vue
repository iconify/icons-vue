<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="yrpa296zp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:minimalist-phone" /></template>
<style>
.yrpa296zp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 2.5c11.874 0 21.5 9.626 21.5 21.5h0c0 11.874-9.626 21.5-21.5 21.5h0C12.126 45.5 2.5 35.874 2.5 24h0A21.43 21.43 0 0 1 8.797 8.797");
}

</style>
