<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e9c5mft3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:slide-text-cursor-24-regular" /></template>
<style>
.e9c5mft3y {
  fill: currentColor;
  d: path("M6.75 8a.75.75 0 0 0 0 1.5h3.5a.75.75 0 0 0 0-1.5zM6 11.75a.75.75 0 0 1 .75-.75h7.424c-.11.23-.17.484-.17.75v.75H6.75a.75.75 0 0 1-.75-.75m14.5-5v7.649l1.5 1.663V6.75A2.75 2.75 0 0 0 19.25 4H4.75A2.75 2.75 0 0 0 2 6.75v10.5A2.75 2.75 0 0 0 4.75 20H14l.001-1.5H4.75c-.69 0-1.25-.56-1.25-1.25V6.75c0-.69.56-1.25 1.25-1.25h14.5c.69 0 1.25.56 1.25 1.25M6.75 14a.75.75 0 0 0 0 1.5h5.5a.75.75 0 0 0 0-1.5zm8.736-2.95a.75.75 0 0 1 .826.198l6.365 7.057a.75.75 0 0 1-.738 1.23l-3.537-.878l-2.03 3.015a.75.75 0 0 1-1.372-.42l.005-9.502a.75.75 0 0 1 .48-.7");
}

</style>
