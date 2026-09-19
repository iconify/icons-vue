<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eldfiimtd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:screener-in" /></template>
<style>
.eldfiimtd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.962 5.5h8.539v37h-8.539zm-14.231 9.75h8.539V42.5h-8.539zM5.5 24h8.539v18.5H5.5z");
}

</style>
