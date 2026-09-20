<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="w25l-4bds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:presence-dnd-12-filled" /></template>
<style>
.w25l-4bds {
  fill: currentColor;
  d: path("M6 12A6 6 0 1 0 6 0a6 6 0 0 0 0 12M3.75 5.25h4.5a.75.75 0 0 1 0 1.5h-4.5a.75.75 0 0 1 0-1.5");
}

</style>
