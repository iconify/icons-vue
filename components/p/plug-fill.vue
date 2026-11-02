<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jk285gc3v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:plug-fill" /></template>
<style>
.jk285gc3v {
  fill: currentColor;
  d: path("M10 6h4V3a1 1 0 0 1 2 0v3a3 3 0 0 1 3 3v6a3 3 0 0 1-3 3h-3v3a1 1 0 0 1-2 0v-3H8a3 3 0 0 1-3-3V9a3 3 0 0 1 3-3V3a1 1 0 0 1 2 0Z");
}

</style>
