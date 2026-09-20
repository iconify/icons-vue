<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xsu7-eb_z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-position-square-right-24-regular" /></template>
<style>
.xsu7-eb_z {
  fill: currentColor;
  d: path("M20.25 4a.75.75 0 0 1 0 1.5H3.75a.75.75 0 0 1 0-1.5zm-9.5 3.5a.75.75 0 0 1 0 1.5h-7a.75.75 0 1 1 0-1.5zm.75 7.75a.75.75 0 0 0-.75-.75h-7a.75.75 0 0 0 0 1.5h7a.75.75 0 0 0 .75-.75M10.75 11a.75.75 0 0 1 0 1.5h-7a.75.75 0 0 1 0-1.5zM21 18.75a.75.75 0 0 0-.75-.75H3.75a.75.75 0 0 0 0 1.5h16.5a.75.75 0 0 0 .75-.75M19.5 11a2.5 2.5 0 0 0-5 0v4.75a.75.75 0 0 1-1.5 0V11a4 4 0 0 1 8 0v4.75a.75.75 0 0 1-1.5 0z");
}

</style>
