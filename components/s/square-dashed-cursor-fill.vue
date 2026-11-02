<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vyfxsyxnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-cursor-fill" /></template>
<style>
.vyfxsyxnj {
  fill: currentColor;
  d: path("M2 5a3 3 0 0 1 3-3h1a1 1 0 0 1 0 2H5a.997.997 0 0 0-1 1v1a1 1 0 0 1-2 0Zm12-3a1 1 0 0 1 0 2h-4a1 1 0 0 1 0-2Zm5 0a3 3 0 0 1 3 3v1a1 1 0 0 1-2 0V5a1 1 0 0 0-1-1h-1a1 1 0 0 1 0-2ZM9.316 8.051l12 4a1 1 0 0 1-.073 1.919l-2.287.572l.751.751a2.414 2.414 0 0 1 0 3.414l-1 1a2.414 2.414 0 0 1-3.414 0l-.751-.751l-.572 2.287a1 1 0 0 1-1.919.073l-4-12a1.001 1.001 0 0 1 1.265-1.265M2 10a1 1 0 0 1 2 0v4a1 1 0 0 1-2 0Zm3 12a3 3 0 0 1-3-3v-1a1 1 0 0 1 2 0v1a1 1 0 0 0 1 1h1a1 1 0 0 1 0 2Z");
}

</style>
