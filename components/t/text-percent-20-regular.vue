<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="qxei_7k4v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-percent-20-regular" /></template>
<style>
.qxei_7k4v {
  fill: currentColor;
  d: path("M14.662 3.085a.5.5 0 0 1 .135.695L6.03 16.778a.5.5 0 1 1-.829-.56L13.968 3.22a.5.5 0 0 1 .694-.135M6 4a2 2 0 1 0 0 4a2 2 0 0 0 0-4M3 6a3 3 0 1 1 6 0a3 3 0 0 1-6 0m9 8a2 2 0 1 1 4 0a2 2 0 0 1-4 0m2-3a3 3 0 1 0 0 6a3 3 0 0 0 0-6");
}

</style>
