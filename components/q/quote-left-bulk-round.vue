<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pg3t-zkoz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:quote-left-bulk-round" /></template>
<style>
.pg3t-zkoz {
  fill: currentColor;
  d: path("M3 11c0-1.33.522-2.597 1.464-3.536A5 5 0 0 1 8 6a1 1 0 0 1 0 2c-1.27 0-2.405.804-2.83 2H7a4 4 0 1 1-4 4Zm2 1v2a2 2 0 1 0 2-2Zm8-1c0-1.33.522-2.597 1.464-3.536A5 5 0 0 1 18 6a1 1 0 0 1 0 2c-1.27 0-2.405.804-2.83 2H17a4 4 0 1 1-4 4Zm2 1v2a2 2 0 1 0 2-2Z");
}

</style>
