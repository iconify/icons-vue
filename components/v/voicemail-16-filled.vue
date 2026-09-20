<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="go9i0pb4q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:voicemail-16-filled" /></template>
<style>
.go9i0pb4q {
  fill: currentColor;
  d: path("M5 7.75a.75.75 0 1 1 1.5 0a.75.75 0 0 1-1.5 0m4.5 0a.75.75 0 1 1 1.5 0a.75.75 0 0 1-1.5 0M3.5 3A1.5 1.5 0 0 0 2 4.5V11a1.5 1.5 0 0 0 1.5 1.5h9A1.5 1.5 0 0 0 14 11V4.5A1.5 1.5 0 0 0 12.5 3zm4 4.75A1.75 1.75 0 1 1 5.75 6h4.5a1.75 1.75 0 1 1-1.582 1H7.332c.108.227.168.482.168.75");
}

</style>
