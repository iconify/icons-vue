<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fnpgyh0wd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-swipe-left-alt" /></template>
<style>
.fnpgyh0wd {
  fill: currentColor;
  d: path("M10.1 13a5 5 0 1 0 0-2H5.83l1.59-1.59L6 8l-4 4l4 4l1.41-1.41L5.83 13z");
}

</style>
