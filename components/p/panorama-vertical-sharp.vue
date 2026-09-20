<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="o5zrrdl4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:panorama-vertical-sharp" /></template>
<style>
.o5zrrdl4b {
  fill: currentColor;
  d: path("M3.475 21.95q.875-1.875 1.45-4.5t.575-5.5t-.575-5.5t-1.45-4.5H20.5q-.875 1.875-1.437 4.5t-.563 5.5t.563 5.5t1.437 4.5z");
}

</style>
