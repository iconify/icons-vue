<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l8lkdj5vf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:mark-email-read-outline-sharp" /></template>
<style>
.l8lkdj5vf {
  fill: currentColor;
  d: path("m15.95 22l-4.25-4.25l1.4-1.4l2.85 2.85l5.65-5.65l1.4 1.4zM12 11l8-5H4zm0 2L4 8v10h5.15l2 2H2V4h20v6.35l-2 2V8zm0 0");
}

</style>
