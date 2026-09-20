<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sj0-uvi8j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:rectangle-portrait-16-regular" /></template>
<style>
.sj0-uvi8j {
  fill: currentColor;
  d: path("M5.5 15A2.5 2.5 0 0 1 3 12.5v-9A2.5 2.5 0 0 1 5.5 1h5A2.5 2.5 0 0 1 13 3.5v9a2.5 2.5 0 0 1-2.5 2.5zM4 12.5A1.5 1.5 0 0 0 5.5 14h5a1.5 1.5 0 0 0 1.5-1.5v-9A1.5 1.5 0 0 0 10.5 2h-5A1.5 1.5 0 0 0 4 3.5z");
}

</style>
