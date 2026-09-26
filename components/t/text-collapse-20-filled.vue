<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wnhgtgl3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-collapse-20-filled" /></template>
<style>
.wnhgtgl3y {
  fill: currentColor;
  d: path("M17.25 15a.75.75 0 0 1 0 1.5H3.75a.75.75 0 0 1 0-1.5zM4.5 6a3.5 3.5 0 1 1 0 7a3.5 3.5 0 0 1 0-7M2.75 9a.5.5 0 0 0 0 1h3.5a.5.5 0 0 0 0-1zm14.5 2a.75.75 0 0 1 0 1.5h-6.5a.75.75 0 0 1 0-1.5zm0-4a.75.75 0 0 1 0 1.5h-6.5a.75.75 0 0 1 0-1.5zm0-4a.75.75 0 0 1 0 1.5H3.75a.75.75 0 0 1 0-1.5z");
}

</style>
