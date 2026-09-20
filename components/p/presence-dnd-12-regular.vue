<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="r47lkgb7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:presence-dnd-12-regular" /></template>
<style>
.r47lkgb7q {
  fill: currentColor;
  d: path("M6 0a6 6 0 1 0 0 12A6 6 0 0 0 6 0M1.5 6a4.5 4.5 0 1 1 9 0a4.5 4.5 0 0 1-9 0M3 6a.75.75 0 0 1 .75-.75h4.5a.75.75 0 0 1 0 1.5h-4.5A.75.75 0 0 1 3 6");
}

</style>
