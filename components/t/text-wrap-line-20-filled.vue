<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ryosshh4o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-wrap-line-20-filled" /></template>
<style>
.ryosshh4o {
  fill: currentColor;
  d: path("M3.5 2.75a.75.75 0 0 0 0 1.5h13a.75.75 0 0 0 0-1.5zm0 12a.75.75 0 0 0 0 1.5h13a.75.75 0 0 0 0-1.5zm7.25-2.25a.75.75 0 0 1 .75-.75h5a.75.75 0 0 1 0 1.5h-5a.75.75 0 0 1-.75-.75m-6.5-4a2.25 2.25 0 0 1 4.5 0v5a.75.75 0 0 0 1.5 0v-5a3.75 3.75 0 1 0-7.5 0v5a.75.75 0 0 0 1.5 0z");
}

</style>
