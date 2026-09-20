<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q8cqs7bmv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-cell-cross-16-filled" /></template>
<style>
.q8cqs7bmv {
  fill: currentColor;
  d: path("M11 13.5A1.5 1.5 0 0 1 9.5 15h-3A1.5 1.5 0 0 1 5 13.5V12h6zM4 11H2.5A1.5 1.5 0 0 1 1 9.5v-3A1.5 1.5 0 0 1 2.5 5H4zm7 0H5V5h6zm2.5-6A1.5 1.5 0 0 1 15 6.5v3a1.5 1.5 0 0 1-1.5 1.5H12V5zm-4-4A1.5 1.5 0 0 1 11 2.5V4H5V2.5A1.5 1.5 0 0 1 6.5 1z");
}

</style>
