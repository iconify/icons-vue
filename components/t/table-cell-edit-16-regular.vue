<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="mrsmzwbhz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-cell-edit-16-regular" /></template>
<style>
.mrsmzwbhz {
  fill: currentColor;
  d: path("m10.944 5l-1 1H6v3.982c-.234.304-.412.65-.524 1.018H3.5A1.5 1.5 0 0 1 2 9.5v-3A1.5 1.5 0 0 1 3.5 5zM3 9.5a.5.5 0 0 0 .5.5H5V6H3.5a.5.5 0 0 0-.5.5zm3.98.877l4.83-4.83a1.87 1.87 0 1 1 2.644 2.646l-4.83 4.829a2.2 2.2 0 0 1-1.02.578l-1.498.374a.89.89 0 0 1-1.079-1.078l.375-1.498a2.2 2.2 0 0 1 .578-1.02");
}

</style>
