<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="gbkkt03yx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-bullet-list-rtl-16-filled" /></template>
<style>
.gbkkt03yx {
  fill: currentColor;
  d: path("M13.75 5a1.25 1.25 0 1 1 0-2.5a1.25 1.25 0 0 1 0 2.5m0 4.25a1.25 1.25 0 1 1 0-2.5a1.25 1.25 0 0 1 0 2.5m-1.25 3a1.25 1.25 0 1 0 2.5 0a1.25 1.25 0 0 0-2.5 0M10.25 3a.75.75 0 0 1 0 1.5h-8.5a.75.75 0 0 1 0-1.5zM11 8a.75.75 0 0 0-.75-.75h-8.5a.75.75 0 0 0 0 1.5h8.5A.75.75 0 0 0 11 8m-.75 3.5a.75.75 0 0 1 0 1.5h-8.5a.75.75 0 0 1 0-1.5z");
}

</style>
