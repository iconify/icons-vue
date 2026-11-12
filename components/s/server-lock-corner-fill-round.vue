<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pnzcbb58b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:server-lock-corner-fill-round" /></template>
<style>
.pnzcbb58b {
  fill: currentColor;
  d: path("M6 3h12a4 4 0 0 1 0 8H6a4 4 0 0 1 0-8m1.01 3H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M14 15a3 3 0 1 1 6 0v.171A3 3 0 0 1 22 18v1a3 3 0 0 1-3 3h-4a3 3 0 0 1-3-3v-1c0-1.27.803-2.405 2-2.829Zm-5 6H6a4 4 0 0 1 0-8h3a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1m7-6h2a1 1 0 0 0-2 0m-8.99 1H7a1 1 0 0 0 0 2h.01a1 1 0 0 0 0-2M15 17a1 1 0 0 0-1 1v1a1 1 0 0 0 1 1h4a1 1 0 0 0 1-1v-1a1 1 0 0 0-1-1Z");
}

</style>
