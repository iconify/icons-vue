<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j0yo5d3bx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-forward" /></template>
<style>
.j0yo5d3bx {
  fill: currentColor;
  d: path("M12 8V6.41c0-.89 1.08-1.34 1.71-.71l5.59 5.59c.39.39.39 1.02 0 1.41l-5.59 5.59c-.63.63-1.71.19-1.71-.7V16H5c-.55 0-1-.45-1-1V9c0-.55.45-1 1-1z");
}

</style>
