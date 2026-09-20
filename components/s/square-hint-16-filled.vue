<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="m1fe9r_1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:square-hint-16-filled" /></template>
<style>
.m1fe9r_1q {
  fill: currentColor;
  d: path("M7.25 2a.75.75 0 0 0 0 1.5h1.5a.75.75 0 0 0 0-1.5zM3.5 7.25a.75.75 0 0 0-1.5 0v1.502a.75.75 0 1 0 1.5 0zm9.75-.75a.75.75 0 0 1 .75.75v1.502a.75.75 0 0 1-1.5 0V7.25a.75.75 0 0 1 .75-.75m-6 7.5a.75.75 0 0 1 0-1.5h1.5a.75.75 0 0 1 0 1.5zM11 2.75a.75.75 0 0 1 .75-.75A2.25 2.25 0 0 1 14 4.25a.75.75 0 0 1-1.5 0a.75.75 0 0 0-.75-.75a.75.75 0 0 1-.75-.75M11.75 14a.75.75 0 0 1 0-1.5a.75.75 0 0 0 .75-.75a.75.75 0 0 1 1.5 0A2.25 2.25 0 0 1 11.75 14M5 2.75A.75.75 0 0 0 4.25 2A2.25 2.25 0 0 0 2 4.25a.75.75 0 0 0 1.5 0a.75.75 0 0 1 .75-.75a.75.75 0 0 0 .75-.75M4.25 14a.75.75 0 0 0 0-1.5a.75.75 0 0 1-.75-.75a.75.75 0 0 0-1.5 0A2.25 2.25 0 0 0 4.25 14");
}

</style>
