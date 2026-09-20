<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y_1r4bceq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:shapes-32-regular" /></template>
<style>
.y_1r4bceq {
  fill: currentColor;
  d: path("M5 12a7 7 0 0 1 13.839-1.5h2.037A9 9 0 1 0 10.5 20.876v-2.037A7 7 0 0 1 5 12m11.5 0a4.5 4.5 0 0 0-4.5 4.5v8a4.5 4.5 0 0 0 4.5 4.5h8a4.5 4.5 0 0 0 4.5-4.5v-8a4.5 4.5 0 0 0-4.5-4.5zM14 16.5a2.5 2.5 0 0 1 2.5-2.5h8a2.5 2.5 0 0 1 2.5 2.5v8a2.5 2.5 0 0 1-2.5 2.5h-8a2.5 2.5 0 0 1-2.5-2.5z");
}

</style>
