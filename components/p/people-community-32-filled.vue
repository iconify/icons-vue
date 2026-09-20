<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="x7vowyyrz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:people-community-32-filled" /></template>
<style>
.x7vowyyrz {
  fill: currentColor;
  d: path("M11.5 7.5a4.5 4.5 0 1 1 9 0a4.5 4.5 0 0 1-9 0M6 6a4 4 0 1 0 0 8a4 4 0 0 0 0-8m20 0a4 4 0 1 0 0 8a4 4 0 0 0 0-8M8.5 16.5q0-.334.053-.651l-4.7 1.259a2.5 2.5 0 0 0-1.767 3.062l.906 3.38a6 6 0 0 0 7.996 4.03A7.48 7.48 0 0 1 8.5 22zm15 5.5a7.48 7.48 0 0 1-2.49 5.58q.315.124.647.213a6 6 0 0 0 7.348-4.243l.906-3.38a2.5 2.5 0 0 0-1.768-3.062l-4.696-1.259q.053.319.053.651zm-11-8a2.5 2.5 0 0 0-2.5 2.5V22a6 6 0 0 0 12 0v-5.5a2.5 2.5 0 0 0-2.5-2.5z");
}

</style>
