<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eae5q3bkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:silo-fill-round" /></template>
<style>
.eae5q3bkk {
  fill: currentColor;
  d: path("M13 9.618V12H3V8a5 5 0 0 1 9.96-.638l5.487 2.744c1.075.537 2.552 1.546 2.553 2.894v7a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2v-2h10v2h6v-6.969c-.051-.125-.154-.231-.247-.324c-.343-.343-.769-.597-1.2-.813ZM13 14v2H3v-2Z");
}

</style>
