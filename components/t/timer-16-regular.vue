<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="ffol5swjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:timer-16-regular" /></template>
<style>
.ffol5swjl {
  fill: currentColor;
  d: path("M5 1.5a.5.5 0 0 1 .5-.5h4a.5.5 0 0 1 0 1h-4a.5.5 0 0 1-.5-.5M7.5 5a.5.5 0 0 0-.5.5v4a.5.5 0 0 0 1 0v-4a.5.5 0 0 0-.5-.5m6 4a6 6 0 1 1-12 0a6 6 0 0 1 12 0m-1 0a5 5 0 1 0-10 0a5 5 0 0 0 10 0m-.047-6.358a.5.5 0 1 0-.707.707l1.403 1.403a.5.5 0 1 0 .707-.707z");
}

</style>
