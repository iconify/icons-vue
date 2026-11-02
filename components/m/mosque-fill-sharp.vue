<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fxx8adbas"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:mosque-fill-sharp" /></template>
<style>
.fxx8adbas {
  fill: currentColor;
  d: path("M13 6.829v1.27A5.02 5.02 0 0 1 16.901 12H19v-2a1 1 0 0 1-1-1c0-.539.014-1.064.163-1.587c.204-.712.598-1.357 1.005-1.968a1 1 0 0 1 1.664 0c.407.611.801 1.256 1.005 1.968C21.986 7.936 22 8.461 22 9a1 1 0 0 1-1 1v11a1 1 0 0 1-1 1h-5v-3a3 3 0 1 0-6 0v3H4a1 1 0 0 1-1-1V10a1 1 0 0 1-1-1c0-.539.014-1.064.163-1.587c.204-.712.598-1.357 1.005-1.968a1 1 0 0 1 1.664 0c.407.611.801 1.256 1.005 1.968C5.986 7.936 6 8.461 6 9a1 1 0 0 1-1 1v2h2.099A5.02 5.02 0 0 1 11 8.099v-1.27a3.002 3.002 0 0 1-1.121-4.95a1 1 0 1 1 1.414 1.414a.999.999 0 1 0 1.414 1.414a1 1 0 0 1 1.414 1.414A3 3 0 0 1 13 6.829");
}

</style>
