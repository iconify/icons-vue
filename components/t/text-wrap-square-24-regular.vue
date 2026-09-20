<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_bzsdovg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-wrap-square-24-regular" /></template>
<style>
.q_bzsdovg {
  fill: currentColor;
  d: path("M3.75 4a.75.75 0 0 0 0 1.5h16.5a.75.75 0 0 0 0-1.5zM3 8.25a.75.75 0 0 1 .75-.75h2a.75.75 0 0 1 0 1.5h-2A.75.75 0 0 1 3 8.25m14.5 0a.75.75 0 0 1 .75-.75h2a.75.75 0 0 1 0 1.5h-2a.75.75 0 0 1-.75-.75M3.75 11a.75.75 0 0 0 0 1.5h2a.75.75 0 0 0 0-1.5zm13.75.75a.75.75 0 0 1 .75-.75h2a.75.75 0 0 1 0 1.5h-2a.75.75 0 0 1-.75-.75M3.75 14.5a.75.75 0 0 0 0 1.5h2a.75.75 0 0 0 0-1.5zm13.75.75a.75.75 0 0 1 .75-.75h2a.75.75 0 0 1 0 1.5h-2a.75.75 0 0 1-.75-.75M3 18.75a.75.75 0 0 1 .75-.75h16.5a.75.75 0 0 1 0 1.5H3.75a.75.75 0 0 1-.75-.75M9.5 11a2.5 2.5 0 0 1 5 0v4.75a.75.75 0 0 0 1.5 0V11a4 4 0 0 0-8 0v4.75a.75.75 0 0 0 1.5 0z");
}

</style>
