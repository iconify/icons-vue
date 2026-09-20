<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="zynj9d18z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:storage-16-regular" /></template>
<style>
.zynj9d18z {
  fill: currentColor;
  d: path("M1 6.5A2.5 2.5 0 0 1 3.5 4h9A2.5 2.5 0 0 1 15 6.5v2a2.5 2.5 0 0 1-2.5 2.5h-9A2.5 2.5 0 0 1 1 8.5zM3.5 5A1.5 1.5 0 0 0 2 6.5v2A1.5 1.5 0 0 0 3.5 10h9A1.5 1.5 0 0 0 14 8.5v-2A1.5 1.5 0 0 0 12.5 5zM10 7a1 1 0 1 1-2 0a1 1 0 0 1 2 0m2 1a1 1 0 1 0 0-2a1 1 0 0 0 0 2");
}

</style>
