<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lkvqjgbkl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-dashed-square-top-left-fill-sharp" /></template>
<style>
.lkvqjgbkl {
  fill: currentColor;
  d: path("M2 14V3a1 1 0 0 1 1-1h11a1 1 0 0 1 1 1v11a1 1 0 0 1-1 1H3a1 1 0 0 1-1-1M21 2a1 1 0 0 1 1 1v3a1 1 0 0 1-2 0V4h-2a1 1 0 0 1 0-2Zm1 12a1 1 0 0 1-2 0v-4a1 1 0 0 1 2 0ZM3 22a1 1 0 0 1-1-1v-3a1 1 0 0 1 2 0v2h2a1 1 0 0 1 0 2Zm19-1a1 1 0 0 1-1 1h-3a1 1 0 0 1 0-2h2v-2a1 1 0 0 1 2 0Zm-12 1a1 1 0 0 1 0-2h4a1 1 0 0 1 0 2Z");
}

</style>
