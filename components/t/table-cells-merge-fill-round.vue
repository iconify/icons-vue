<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r20pbs6eb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:table-cells-merge-fill-round" /></template>
<style>
.r20pbs6eb {
  fill: currentColor;
  d: path("M3 8a5 5 0 0 1 5-5h3v5Zm18 0h-8V3h3a5 5 0 0 1 5 5M3 10h18v4H3Zm0 6h8v5H8a5 5 0 0 1-5-5m18 0a5 5 0 0 1-1.464 3.536A5 5 0 0 1 16 21h-3v-5Z");
}

</style>
