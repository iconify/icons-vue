<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="oy0gdib9p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:threat-actor-16-filled" /></template>
<style>
.oy0gdib9p {
  fill: currentColor;
  d: path("M15 10.438a3.563 3.563 0 0 1-6.035 2.564l-.618-.596a.5.5 0 0 0-.694 0l-.618.596A3.563 3.563 0 0 1 1 10.437V8h14zM2.984 9.63a1.75 1.75 0 0 0 3.032 1.75zm7 1.75a1.75 1.75 0 0 0 3.032-1.75zM7.998 1a6.99 6.99 0 0 1 5.744 3h.758a1 1 0 0 1 1 1v1a1 1 0 0 1-1 1h-13a1 1 0 0 1-1-1V5a1 1 0 0 1 1-1h.754a6.99 6.99 0 0 1 5.744-3");
}

</style>
