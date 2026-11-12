<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m79q95bhn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:segmented-control-fill-sharp" /></template>
<style>
.m79q95bhn {
  fill: currentColor;
  d: path("M2 6a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1Zm2 1v10h16V7Zm1 8V9a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1m12.01-4a1 1 0 0 1 0 2H17a1 1 0 0 1 0-2Z");
}

</style>
