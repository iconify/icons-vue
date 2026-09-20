<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="c98dkjv4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:panel-top-gallery-20-regular" /></template>
<style>
.c98dkjv4o {
  fill: currentColor;
  d: path("M5 4a3 3 0 0 0-3 3v6a3 3 0 0 0 3 3h10a3 3 0 0 0 3-3V7a3 3 0 0 0-3-3zM3 7a2 2 0 0 1 2-2h2v4H3zm0 3h14v3a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2zm14-1h-4V5h2a2 2 0 0 1 2 2zm-5-4v4H8V5z");
}

</style>
