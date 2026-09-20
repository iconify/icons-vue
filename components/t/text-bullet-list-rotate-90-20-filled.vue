<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="pcd_s6dns"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-bullet-list-rotate-90-20-filled" /></template>
<style>
.pcd_s6dns {
  fill: currentColor;
  d: path("M4.5 4a1 1 0 1 0 0-2a1 1 0 0 0 0 2ZM10 4a1 1 0 1 0 0-2a1 1 0 0 0 0 2Zm6.5-1a1 1 0 1 1-2 0a1 1 0 0 1 2 0ZM5.25 5.75a.75.75 0 0 0-1.5 0v11.5a.75.75 0 0 0 1.5 0V5.75ZM10 5a.75.75 0 0 1 .75.75v11.5a.75.75 0 0 1-1.5 0V5.75A.75.75 0 0 1 10 5Zm6.25.75a.75.75 0 0 0-1.5 0v11.5a.75.75 0 0 0 1.5 0V5.75Z");
}

</style>
