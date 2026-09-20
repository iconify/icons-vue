<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zn32db0km"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:weather-sunny-low-24-regular" /></template>
<style>
.zn32db0km {
  fill: currentColor;
  d: path("M12.75 2.75a.75.75 0 0 0-1.5 0v1.5a.75.75 0 0 0 1.5 0zm6.28 2.22a.75.75 0 0 1 0 1.06l-1.06 1.061a.75.75 0 0 1-1.061-1.06l1.06-1.061a.75.75 0 0 1 1.061 0M17.41 13q.09-.487.09-1a5.5 5.5 0 1 0-10.91 1H2.75a.75.75 0 0 0 0 1.5h18.5a.75.75 0 0 0 0-1.5zM12 8a4 4 0 0 1 3.874 5H8.126A4 4 0 0 1 12 8m-6 8.75a.75.75 0 0 1 .75-.75h10.5a.75.75 0 0 1 0 1.5H6.75a.75.75 0 0 1-.75-.75m4 3a.75.75 0 0 1 .75-.75h2.5a.75.75 0 0 1 0 1.5h-2.5a.75.75 0 0 1-.75-.75M4.97 4.97a.75.75 0 0 1 1.06 0l1.061 1.06a.75.75 0 1 1-1.06 1.061L4.97 6.031a.75.75 0 0 1 0-1.061");
}

</style>
