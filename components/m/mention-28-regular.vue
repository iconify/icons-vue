<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="v06z1ibxp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mention-28-regular" /></template>
<style>
.v06z1ibxp {
  fill: currentColor;
  d: path("M14 2c6.627 0 12 5.373 12 12c0 3.7-1.9 6-4.25 6c-1.546 0-2.897-.996-3.64-2.731C17.14 18.897 15.462 20 13.5 20C10.394 20 8 17.241 8 14s2.394-6 5.5-6c1.599 0 3.008.732 4 1.883V8.75a.75.75 0 0 1 1.5 0V14l.005.304c.095 3.07 1.631 4.196 2.745 4.196c1.15 0 2.75-1.2 2.75-4.5c0-5.799-4.701-10.5-10.5-10.5S3.5 8.201 3.5 14S8.201 24.5 14 24.5c1.428 0 2.79-.286 4.031-.803a.8.8 0 0 1 .88.162c.363.364.271.977-.202 1.18A11.95 11.95 0 0 1 14 26C7.373 26 2 20.627 2 14S7.373 2 14 2m-.5 7.5c-2.14 0-4 1.942-4 4.5s1.86 4.5 4 4.5s4-1.942 4-4.5s-1.86-4.5-4-4.5");
}

</style>
