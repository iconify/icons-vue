<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="yk29x_bpl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:storage-16-filled" /></template>
<style>
.yk29x_bpl {
  fill: currentColor;
  d: path("M3.5 4A2.5 2.5 0 0 0 1 6.5v2A2.5 2.5 0 0 0 3.5 11h9A2.5 2.5 0 0 0 15 8.5v-2A2.5 2.5 0 0 0 12.5 4zM10 7a1 1 0 1 1-2 0a1 1 0 0 1 2 0m2 1a1 1 0 1 1 0-2a1 1 0 0 1 0 2");
}

</style>
