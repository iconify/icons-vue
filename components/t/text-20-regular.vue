<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m3wh9rs9d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-20-regular" /></template>
<style>
.m3wh9rs9d {
  fill: currentColor;
  d: path("M4 3.5a.5.5 0 0 1 .5-.5h10a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-1 0V4h-4v12h1.5a.5.5 0 0 1 0 1h-4a.5.5 0 0 1 0-1H9V4H5v1.5a.5.5 0 0 1-1 0z");
}

</style>
