<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wdwdnc-wi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:warehouse-fill" /></template>
<style>
.wdwdnc-wi {
  fill: currentColor;
  d: path("M17 22v-8a3 3 0 0 0-3-3h-4a3 3 0 0 0-3 3v8H6a3 3 0 0 1-3-3V9.236a3 3 0 0 1 1.658-2.683L9.13 4.317c.417-.21.876-.318 1.342-.317h3.056c.466-.001.925.107 1.342.317l4.472 2.236A3 3 0 0 1 21 9.236V19a3 3 0 0 1-3 3Zm-8-6v-2a.997.997 0 0 1 1-1h4a.997.997 0 0 1 1 1v2Zm0 6v-4h6v4Z");
}

</style>
