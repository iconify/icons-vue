<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mj2nxs_yh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:walgreens" /></template>
<style>
.mj2nxs_yh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 16.5c4.42-4.877 11.095.884 14.935-3.505c-4.053 5.883-15.522 19.377-7.223 22.434c9.268 3.414 24.536-15.911 19.263-19.142c-5.13-3.143-15.453 18.532-4.785 20.026c9.494 1.329 19.355-18.502 16.215-24.69");
}

</style>
