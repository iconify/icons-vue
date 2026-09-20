<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="t9sd7fboe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:shape-exclude-16-filled" /></template>
<style>
.t9sd7fboe {
  fill: currentColor;
  d: path("M3 2.268A2 2 0 0 0 2 4v5a2 2 0 0 0 2 2h1v1a2 2 0 0 0 2 2h5a2 2 0 0 0 2-2V7a2 2 0 0 0-2-2h-1V4a2 2 0 0 0-2-2H4a2 2 0 0 0-1 .268M11 5v4a2 2 0 0 1-2 2H5V7a2 2 0 0 1 2-2z");
}

</style>
