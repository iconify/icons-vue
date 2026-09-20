<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="m5o01091t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:padding-right-20-regular" /></template>
<style>
.m5o01091t {
  fill: currentColor;
  d: path("M15.854 9.854a.5.5 0 0 0 0-.708l-4.5-4.5a.5.5 0 0 0-.708.708L14.293 9H4.5a.5.5 0 0 0 0 1h9.793l-3.647 3.646a.5.5 0 0 0 .708.708zM3 3.5a.5.5 0 0 0-1 0v12a.5.5 0 0 0 1 0zm15 0a.5.5 0 0 0-1 0v1a.5.5 0 0 0 1 0zm0 3a.5.5 0 0 0-1 0v2a.5.5 0 0 0 1 0zm0 4a.5.5 0 0 0-1 0v2a.5.5 0 0 0 1 0zm0 4a.5.5 0 0 0-1 0v1a.5.5 0 0 0 1 0z");
}

</style>
