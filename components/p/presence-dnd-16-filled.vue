<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oglyhrbos"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:presence-dnd-16-filled" /></template>
<style>
.oglyhrbos {
  fill: currentColor;
  d: path("M8 16A8 8 0 1 0 8 0a8 8 0 0 0 0 16M5.249 7h5.5a1 1 0 1 1 0 2h-5.5a1 1 0 1 1 0-2");
}

</style>
