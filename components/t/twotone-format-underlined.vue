<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pa33txxku"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:twotone-format-underlined" /></template>
<style>
.pa33txxku {
  fill: currentColor;
  d: path("M5 19h14v2H5zM6 3v8c0 3.31 2.69 6 6 6s6-2.69 6-6V3h-2.5v8c0 1.93-1.57 3.5-3.5 3.5S8.5 12.93 8.5 11V3z");
}

</style>
