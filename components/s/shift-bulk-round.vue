<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jq-y894ln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:shift-bulk-round" /></template>
<style>
.jq-y894ln {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 20h-2a3 3 0 0 1-3-3v-2a.997.997 0 0 0-1-1H6c-.898 0-1.928-.572-2.089-1.521a1.34 1.34 0 0 1 .382-1.186l6-6a2.414 2.414 0 0 1 3.414 0l6 6c.311.311.456.752.382 1.186C19.928 13.428 18.898 14 18 14h-1a.997.997 0 0 0-1 1v2a3 3 0 0 1-3 3");
}

</style>
