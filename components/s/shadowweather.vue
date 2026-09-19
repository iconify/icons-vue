<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="p50tnjbth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:shadowweather" /></template>
<style>
.p50tnjbth {
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 10;
  d: path("M31.222 15.887A10.918 10.918 0 0 0 11.1 23.474a6.998 6.998 0 0 0 .397 13.985h21.167a10.835 10.835 0 1 0-7.65-18.508");
}

</style>
