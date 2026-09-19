<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x1gwe4bjh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:op-auto-clicker" /></template>
<style>
.x1gwe4bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.865 19.278h10.857C36.979 9.9 32.609 4.11 25.616 4.52zm-3.406 0H11.602C11.345 9.9 15.715 4.11 22.708 4.52zm-11.1 3.64C10.182 41.545 15.345 43.488 24 43.488s13.817-1.944 12.642-20.57z");
}

</style>
