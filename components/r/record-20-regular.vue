<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="tt1q1__up"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:record-20-regular" /></template>
<style>
.tt1q1__up {
  fill: currentColor;
  d: path("M10 14.5a4.5 4.5 0 1 0 0-9a4.5 4.5 0 0 0 0 9M10 2a8 8 0 1 0 0 16a8 8 0 0 0 0-16m-7 8a7 7 0 1 1 14 0a7 7 0 0 1-14 0");
}

</style>
