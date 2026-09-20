<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="popma3toh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-bullet-list-square-16-regular" /></template>
<style>
.popma3toh {
  fill: currentColor;
  d: path("M5.5 5A.75.75 0 1 1 4 5a.75.75 0 0 1 1.5 0m0 3A.75.75 0 1 1 4 8a.75.75 0 0 1 1.5 0m-.75 3.75a.75.75 0 1 0 0-1.5a.75.75 0 0 0 0 1.5M6.5 5a.5.5 0 0 1 .5-.5h4.5a.5.5 0 0 1 0 1H7a.5.5 0 0 1-.5-.5M7 7.5a.5.5 0 0 0 0 1h4.5a.5.5 0 0 0 0-1zM6.5 11a.5.5 0 0 1 .5-.5h4.5a.5.5 0 0 1 0 1H7a.5.5 0 0 1-.5-.5m-2-9A2.5 2.5 0 0 0 2 4.5v7A2.5 2.5 0 0 0 4.5 14h7a2.5 2.5 0 0 0 2.5-2.5v-7A2.5 2.5 0 0 0 11.5 2zM3 4.5A1.5 1.5 0 0 1 4.5 3h7A1.5 1.5 0 0 1 13 4.5v7a1.5 1.5 0 0 1-1.5 1.5h-7A1.5 1.5 0 0 1 3 11.5z");
}

</style>
