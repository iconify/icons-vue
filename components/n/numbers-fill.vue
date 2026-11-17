<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bsfgaac-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:numbers-fill" /></template>
<style>
.bsfgaac-x {
  fill: currentColor;
  d: path("M4.293 6.293A1 1 0 0 1 6 7v10a1 1 0 0 1-2 0V9.414l-.293.293a.999.999 0 1 1-1.414-1.414ZM12 6a2 2 0 0 1 2 2v3a2 2 0 0 1-2 2h-2v3h3a1 1 0 0 1 0 2h-3a2 2 0 0 1-2-2v-3a2 2 0 0 1 2-2h2V8H9a1 1 0 0 1 0-2Zm8 0a2 2 0 0 1 2 2v3c0 .35-.092.696-.267 1c.175.304.267.65.267 1v3a2 2 0 0 1-2 2h-3a1 1 0 0 1 0-2h3v-3h-2a1 1 0 0 1 0-2h2V8h-3a1 1 0 0 1 0-2Z");
}

</style>
