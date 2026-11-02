<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="szmuevw1b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:table-plus-corner-fill" /></template>
<style>
.szmuevw1b {
  fill: currentColor;
  d: path("M11 8H3V6a3 3 0 0 1 3-3h5Zm10-2v2h-8V3h5a3 3 0 0 1 3 3M3 10h7v4H3Zm15 3v3h3a1 1 0 0 1 0 2h-3v3a1 1 0 0 1-2 0v-3h-3a1 1 0 0 1 0-2h3v-3a1 1 0 0 1 2 0M3 16h7v4a1 1 0 0 1-1 1H6a3 3 0 0 1-3-3Z");
}

</style>
