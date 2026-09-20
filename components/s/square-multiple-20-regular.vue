<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="z4j4pebrf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:square-multiple-20-regular" /></template>
<style>
.z4j4pebrf {
  fill: currentColor;
  d: path("M6.085 4H5.05A2.5 2.5 0 0 1 7.5 2H14a4 4 0 0 1 4 4v6.5a2.5 2.5 0 0 1-2 2.45v-1.035a1.5 1.5 0 0 0 1-1.415V6a3 3 0 0 0-3-3H7.5a1.5 1.5 0 0 0-1.415 1M4.5 5A2.5 2.5 0 0 0 2 7.5v8A2.5 2.5 0 0 0 4.5 18h8a2.5 2.5 0 0 0 2.5-2.5v-8A2.5 2.5 0 0 0 12.5 5zM3 7.5A1.5 1.5 0 0 1 4.5 6h8A1.5 1.5 0 0 1 14 7.5v8a1.5 1.5 0 0 1-1.5 1.5h-8A1.5 1.5 0 0 1 3 15.5z");
}

</style>
