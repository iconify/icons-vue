<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i5yfeibeg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-collapse-32-light" /></template>
<style>
.i5yfeibeg {
  fill: currentColor;
  d: path("M29.5 26a.5.5 0 0 1 0 1h-22a.5.5 0 0 1 0-1zM8.75 9a6.75 6.75 0 1 1 0 13.5a6.75 6.75 0 0 1 0-13.5m-3 6a.75.75 0 0 0 0 1.5h6a.75.75 0 0 0 0-1.5zm23.75 4a.5.5 0 0 1 0 1h-11a.5.5 0 0 1 0-1zm0-8a.5.5 0 0 1 0 1h-11a.5.5 0 0 1 0-1zm0-7a.5.5 0 0 1 0 1h-22a.5.5 0 0 1 0-1z");
}

</style>
