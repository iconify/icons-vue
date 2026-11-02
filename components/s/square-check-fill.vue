<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jb4k-rbip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:square-check-fill" /></template>
<style>
.jb4k-rbip {
  fill: currentColor;
  d: path("M2 5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Zm8.933 8.519l-2.226-2.226a.999.999 0 1 0-1.414 1.414l3 3a1 1 0 0 0 1.475-.067l5-6a1 1 0 1 0-1.536-1.28Z");
}

</style>
