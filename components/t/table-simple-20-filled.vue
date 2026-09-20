<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m3g5yzbwz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-simple-20-filled" /></template>
<style>
.m3g5yzbwz {
  fill: currentColor;
  d: path("M5.5 3A2.5 2.5 0 0 0 3 5.5v4h6.5V3zm4 7.5H3v4A2.5 2.5 0 0 0 5.5 17h4zm1 0H17v4a2.5 2.5 0 0 1-2.5 2.5h-4zm6.5-1v-4A2.5 2.5 0 0 0 14.5 3h-4v6.5z");
}

</style>
