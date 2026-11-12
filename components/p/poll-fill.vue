<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qim42yb4k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:poll-fill" /></template>
<style>
.qim42yb4k {
  fill: currentColor;
  d: path("M2 7a3 3 0 1 1 6 0a3 3 0 0 1-6 0m19-1a1 1 0 0 1 0 2H11a1 1 0 0 1 0-2ZM2 17a3 3 0 1 1 6 0a3 3 0 0 1-6 0m15-1a1 1 0 0 1 0 2h-6a1 1 0 0 1 0-2Z");
}

</style>
