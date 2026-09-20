<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ihvf25k6i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-wrap-front-24-regular" /></template>
<style>
.ihvf25k6i {
  fill: currentColor;
  d: path("M3.75 4a.75.75 0 0 0 0 1.5h16.5a.75.75 0 0 0 0-1.5zM12 8.5A2.5 2.5 0 0 0 9.708 10H8.126a4.002 4.002 0 0 1 7.748 0h-1.582A2.5 2.5 0 0 0 12 8.5m-4 5h1.5v2.25a.75.75 0 0 1-1.5 0zm8 0h-1.5v2.25a.75.75 0 0 0 1.5 0zm4.25-2.5a.75.75 0 0 1 0 1.5H3.75a.75.75 0 0 1 0-1.5zM3 18.75a.75.75 0 0 1 .75-.75h16.5a.75.75 0 0 1 0 1.5H3.75a.75.75 0 0 1-.75-.75");
}

</style>
