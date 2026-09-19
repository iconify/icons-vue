<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q628zjb6m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:round-timer" /></template>
<style>
.q628zjb6m {
  fill: currentColor;
  d: path("M10 3h4c.55 0 1-.45 1-1s-.45-1-1-1h-4c-.55 0-1 .45-1 1s.45 1 1 1m9.03 4.39l.75-.75a.993.993 0 0 0 0-1.4l-.01-.01a.993.993 0 0 0-1.4 0l-.75.75A8.96 8.96 0 0 0 12 4c-4.8 0-8.88 3.96-9 8.76A9 9 0 0 0 12 22a8.994 8.994 0 0 0 7.03-14.61M13 13c0 .55-.45 1-1 1s-1-.45-1-1V9c0-.55.45-1 1-1s1 .45 1 1z");
}

</style>
