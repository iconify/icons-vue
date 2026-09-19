<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y52jjfbds"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-format-list-numbered" /></template>
<style>
.y52jjfbds {
  fill: currentColor;
  d: path("M5 13H3.2L5 10.9V10H2v1h1.8L2 13.1v.9h3zm2-8h14v2H7zM5 16H2v1h2v.5H3v1h1v.5H2v1h3zm2 1h14v2H7zM3 8h1V4H2v1h1zm4 3h14v2H7z");
}

</style>
