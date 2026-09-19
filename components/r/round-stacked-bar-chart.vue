<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h0jtq_b-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-stacked-bar-chart" /></template>
<style>
.h0jtq_b-h {
  fill: currentColor;
  d: path("M6 20c1.1 0 2-.9 2-2V9H4v9c0 1.1.9 2 2 2M4 8h4V6c0-1.1-.9-2-2-2s-2 .9-2 2zm6 3h4V9c0-1.1-.9-2-2-2s-2 .9-2 2zm6 1v2h4v-2c0-1.1-.9-2-2-2s-2 .9-2 2m2 8c1.1 0 2-.9 2-2v-3h-4v3c0 1.1.9 2 2 2m-6 0c1.1 0 2-.9 2-2v-6h-4v6c0 1.1.9 2 2 2");
}

</style>
