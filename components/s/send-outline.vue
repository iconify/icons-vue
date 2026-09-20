<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w7ncosbop"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:send-outline" /></template>
<style>
.w7ncosbop {
  fill: currentColor;
  d: path("M3 20V4l19 8zm2-3l11.85-5L5 7v3.5l6 1.5l-6 1.5zm0 0V7z");
}

</style>
