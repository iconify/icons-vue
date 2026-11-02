<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3b0uzbzp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:table-cells-split-fill-sharp" /></template>
<style>
.b3b0uzbzp {
  fill: currentColor;
  d: path("M3 8V4a1 1 0 0 1 1-1h16a1 1 0 0 1 1 1v4Zm0 6v-4h8v4Zm18-4v4h-8v-4ZM3 16h18v4a1 1 0 0 1-1 1H4a1 1 0 0 1-1-1Z");
}

</style>
