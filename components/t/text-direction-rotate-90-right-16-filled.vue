<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="brx7w18be"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-direction-rotate-90-right-16-filled" /></template>
<style>
.brx7w18be {
  fill: currentColor;
  d: path("M4.25 2a.75.75 0 0 1 .75.75v8.69l.72-.72a.75.75 0 0 1 1.06 1.06l-2 2a.75.75 0 0 1-1.06 0l-2-2a.75.75 0 0 1 1.06-1.06l.72.72V2.75A.75.75 0 0 1 4.25 2m6.5 6a.75.75 0 0 1 .75.75v2.69l.72-.72a.75.75 0 0 1 1.06 1.06l-2 2a.75.75 0 0 1-1.06 0l-2-2a.75.75 0 0 1 1.06-1.06l.72.72V8.75a.75.75 0 0 1 .75-.75M6.548 2.486a.75.75 0 0 1 .966-.438l6 2.25l.104.049a.75.75 0 0 1-.104 1.355l-6 2.25a.75.75 0 0 1-.528-1.404L8.5 5.979V4.02l-1.514-.567a.75.75 0 0 1-.438-.966M10 5.417L11.114 5L10 4.582z");
}

</style>
