<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="aqpy5mb3m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:weather-sunny-32-regular" /></template>
<style>
.aqpy5mb3m {
  fill: currentColor;
  d: path("M16 2a1 1 0 0 1 1 1v2a1 1 0 0 1-2 0V3a1 1 0 0 1 1-1m0 21a7 7 0 1 0 0-14a7 7 0 0 0 0 14m0-2a5 5 0 1 1 0-10a5 5 0 0 1 0 10m13-4a1 1 0 0 0 0-2h-2a1 1 0 1 0 0 2zm-13 9a1 1 0 0 1 1 1v2a1 1 0 0 1-2 0v-2a1 1 0 0 1 1-1M5 17a1 1 0 1 0 0-2H3a1 1 0 1 0 0 2zm.294-11.706a1 1 0 0 1 1.414 0l2 2a1 1 0 1 1-1.414 1.414l-2-2a1 1 0 0 1 0-1.414m1.414 21.414a1 1 0 0 1-1.414-1.414l2-2a1 1 0 1 1 1.414 1.414zm20-21.414a1 1 0 0 0-1.414 0l-2 2a1 1 0 0 0 1.414 1.414l2-2a1 1 0 0 0 0-1.414m-1.414 21.414a1 1 0 0 0 1.414-1.414l-2-2a1 1 0 1 0-1.414 1.414z");
}

</style>
