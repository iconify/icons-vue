<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="i1a-c1b_r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pipeline-add-32-filled" /></template>
<style>
.i1a-c1b_r {
  fill: currentColor;
  d: path("M4 6a2 2 0 0 0-2 2v16a2 2 0 1 0 4 0V8a2 2 0 0 0-2-2m24 0a2 2 0 0 0-2 2v6.512a9 9 0 0 1 4 2.83V8a2 2 0 0 0-2-2m-5 8q.508 0 1 .055V9H8v14h6a9 9 0 0 1 9-9m0 16.5a7.5 7.5 0 1 0 0-15a7.5 7.5 0 0 0 0 15m1-12.25V22h3.75a.75.75 0 0 1 0 1.5H24v3.75a.75.75 0 0 1-1.5 0V23.5h-3.75a.75.75 0 0 1 0-1.5h3.75v-3.75a.75.75 0 0 1 1.5 0");
}

</style>
