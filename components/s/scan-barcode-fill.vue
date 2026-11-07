<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="drie8t4tm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:scan-barcode-fill" /></template>
<style>
.drie8t4tm {
  fill: currentColor;
  d: path("M2 7V5a3 3 0 0 1 3-3h2a1 1 0 0 1 0 2H5a.997.997 0 0 0-1 1v2a1 1 0 0 1-2 0m15-5h2a3 3 0 0 1 3 3v2a1 1 0 0 1-2 0V5a1 1 0 0 0-1-1h-2a1 1 0 0 1 0-2M8 8v8a1 1 0 0 1-2 0V8a1 1 0 0 1 2 0m5 0v8a1 1 0 0 1-2 0V8a1 1 0 0 1 2 0m5 0v8a1 1 0 0 1-2 0V8a1 1 0 0 1 2 0M5 22a3 3 0 0 1-3-3v-2a1 1 0 0 1 2 0v2a1 1 0 0 0 1 1h2a1 1 0 0 1 0 2Zm17-5v2a3 3 0 0 1-3 3h-2a1 1 0 0 1 0-2h2a1 1 0 0 0 1-1v-2a1 1 0 0 1 2 0");
}

</style>
