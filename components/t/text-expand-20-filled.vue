<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bt3s3db7a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-expand-20-filled" /></template>
<style>
.bt3s3db7a {
  fill: currentColor;
  d: path("M17.25 15a.75.75 0 0 1 0 1.5H3.75a.75.75 0 0 1 0-1.5zM4.5 6a3.5 3.5 0 1 1 0 7a3.5 3.5 0 0 1 0-7m0 1.25a.5.5 0 0 0-.5.5V9H2.75a.5.5 0 0 0 0 1H4v1.25a.5.5 0 0 0 1 0V10h1.25a.5.5 0 0 0 0-1H5V7.75a.5.5 0 0 0-.5-.5M17.25 11a.75.75 0 0 1 0 1.5h-6.5a.75.75 0 0 1 0-1.5zm0-4a.75.75 0 0 1 0 1.5h-6.5a.75.75 0 0 1 0-1.5zm0-4a.75.75 0 0 1 0 1.5H3.75a.75.75 0 0 1 0-1.5z");
}

</style>
