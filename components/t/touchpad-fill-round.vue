<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l_y0nob3r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:touchpad-fill-round" /></template>
<style>
.l_y0nob3r {
  fill: currentColor;
  d: path("M7 4h10a5 5 0 0 1 5 5v4H2V9a5 5 0 0 1 5-5m4 16H7a5 5 0 0 1-5-5h9Zm11-5a5 5 0 0 1-1.464 3.536A5 5 0 0 1 17 20h-4v-5Z");
}

</style>
