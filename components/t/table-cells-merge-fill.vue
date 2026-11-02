<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fsir0_b0q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:table-cells-merge-fill" /></template>
<style>
.fsir0_b0q {
  fill: currentColor;
  d: path("M11 8H3V6a3 3 0 0 1 3-3h5Zm2-5h5a3 3 0 0 1 3 3v2h-8ZM3 14v-4h18v4Zm8 7H6a3 3 0 0 1-3-3v-2h8Zm10-5v2a3 3 0 0 1-3 3h-5v-5Z");
}

</style>
