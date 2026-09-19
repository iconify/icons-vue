<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jwvozhcnm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:timer-off" /></template>
<style>
.jwvozhcnm {
  fill: currentColor;
  d: path("M9 1h6v2H9zm4 7v2.17l6.98 6.98a8.96 8.96 0 0 0-.95-9.76l1.42-1.42c-.43-.51-.9-.99-1.41-1.41l-1.42 1.42a8.96 8.96 0 0 0-9.77-.96L10.83 8zM2.81 2.81L1.39 4.22l3.4 3.4a8.994 8.994 0 0 0 12.59 12.59l2.4 2.4l1.41-1.41z");
}

</style>
