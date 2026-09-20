<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="wknuyzg7e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:teardrop-bottom-right-16-regular" /></template>
<style>
.wknuyzg7e {
  fill: currentColor;
  d: path("M1 8a7 7 0 0 1 14 0v5.25A1.75 1.75 0 0 1 13.25 15H8a7 7 0 0 1-7-7m7-6a6 6 0 1 0 0 12h5.25a.75.75 0 0 0 .75-.75V8a6 6 0 0 0-6-6");
}

</style>
