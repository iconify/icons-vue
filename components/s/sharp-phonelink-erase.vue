<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m3r5xy_np"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-phonelink-erase" /></template>
<style>
.m3r5xy_np {
  fill: currentColor;
  d: path("m13 8.2l-1-1l-4 4l-4-4l-1 1l4 4l-4 4l1 1l4-4l4 4l1-1l-4-4zM21 1H7v5h2V4h10v16H9v-2H7v5h14z");
}

</style>
