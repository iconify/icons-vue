<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mkl97tirg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-waterfall-chart" /></template>
<style>
.mkl97tirg {
  fill: currentColor;
  d: path("M18 4h3v16h-3zM3 13h3v7H3zm11-9h3v3h-3zm-4 1h3v4h-3zm-3 5h3v4H7z");
}

</style>
