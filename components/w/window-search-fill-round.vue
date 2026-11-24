<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cex7e4bdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:window-search-fill-round" /></template>
<style>
.cex7e4bdk {
  fill: currentColor;
  d: path("M17 21H7a5 5 0 0 1-5-5V8a5 5 0 0 1 5-5h10a5 5 0 0 1 5 5v8a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 21M4 9v7a3.004 3.004 0 0 0 3 3h10a3 3 0 0 0 3-3V9Zm9.708 5.293l1.999 2a.999.999 0 1 1-1.414 1.414l-2-1.999a3 3 0 1 1 1.415-1.415M10 13a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
