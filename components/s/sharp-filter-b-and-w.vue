<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bm8qffoxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-filter-b-and-w" /></template>
<style>
.bm8qffoxq {
  fill: currentColor;
  d: path("M21 3H3v18h18zm-2 16l-7-8v8H5l7-8V5h7z");
}

</style>
