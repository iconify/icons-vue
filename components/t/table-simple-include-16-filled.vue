<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="a2nnj7bzs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-simple-include-16-filled" /></template>
<style>
.a2nnj7bzs {
  fill: currentColor;
  d: path("M4.5 2A2.5 2.5 0 0 0 2 4.5v3h5.264a3 3 0 0 1 .236-.236V2zM2 8.5h4.67c-.11.313-.17.65-.17 1V12c0 .768.289 1.47.764 2H4.5A2.5 2.5 0 0 1 2 11.5zm12-4v2.764a3 3 0 0 0-2-.764H9.5c-.35 0-.687.06-1 .17V2h3A2.5 2.5 0 0 1 14 4.5M7.5 9.25c0-.966.784-1.75 1.75-1.75h3c.966 0 1.75.784 1.75 1.75v3A1.75 1.75 0 0 1 12.25 14h-3a1.75 1.75 0 0 1-1.75-1.75z");
}

</style>
