<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p2927wb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-simple-16-filled" /></template>
<style>
.p2927wb3y {
  fill: currentColor;
  d: path("M4.5 2A2.5 2.5 0 0 0 2 4.5v3h5.5V2zm3 6.5H2v3A2.5 2.5 0 0 0 4.5 14h3zm1 0H14v3a2.5 2.5 0 0 1-2.5 2.5h-3zm5.5-1v-3A2.5 2.5 0 0 0 11.5 2h-3v5.5z");
}

</style>
