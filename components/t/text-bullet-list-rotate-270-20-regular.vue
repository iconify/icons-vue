<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="xm5_6-bcb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-bullet-list-rotate-270-20-regular" /></template>
<style>
.xm5_6-bcb {
  fill: currentColor;
  d: path("M4.5 16a1 1 0 1 1 0 2a1 1 0 0 1 0-2Zm5.5 0a1 1 0 1 1 0 2a1 1 0 0 1 0-2Zm6.5 1a1 1 0 1 0-2 0a1 1 0 0 0 2 0ZM5 14.5a.5.5 0 0 1-1 0v-12a.5.5 0 0 1 1 0v12Zm5 .5a.5.5 0 0 0 .5-.5v-12a.5.5 0 0 0-1 0v12a.5.5 0 0 0 .5.5Zm6-.5a.5.5 0 0 1-1 0v-12a.5.5 0 0 1 1 0v12Z");
}

</style>
