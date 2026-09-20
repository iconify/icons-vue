<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="p7ov9pouy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-line-spacing-16-filled" /></template>
<style>
.p7ov9pouy {
  fill: currentColor;
  d: path("M12.75 9a.75.75 0 0 1 .75.75v2.69l.22-.22a.75.75 0 0 1 1.06 1.06l-1.5 1.5a.75.75 0 0 1-1.004.052l-.056-.052l-1.5-1.5a.75.75 0 0 1 1.06-1.06l.22.22V9.75a.75.75 0 0 1 .75-.75m-6.5 2a.75.75 0 0 1 0 1.5h-4.5a.75.75 0 0 1 0-1.5zm3-4a.75.75 0 0 1 0 1.5h-7.5a.75.75 0 0 1 0-1.5zm3.026-5.832a.75.75 0 0 1 1.004.052l1.5 1.5a.75.75 0 0 1-1.06 1.06l-.22-.22v2.69a.75.75 0 0 1-1.5 0V3.56l-.22.22a.75.75 0 1 1-1.06-1.06l1.5-1.5zM6.25 3a.75.75 0 0 1 0 1.5h-4.5a.75.75 0 0 1 0-1.5z");
}

</style>
