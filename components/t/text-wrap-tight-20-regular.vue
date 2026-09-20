<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wxgsz3b5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-wrap-tight-20-regular" /></template>
<style>
.wxgsz3b5v {
  fill: currentColor;
  d: path("M3 3.5a.5.5 0 0 1 .5-.5h13a.5.5 0 0 1 0 1h-13a.5.5 0 0 1-.5-.5M3.5 6h2.758a4.5 4.5 0 0 0-.502 1H3.5a.5.5 0 0 1 0-1m0 3h2v1h-2a.5.5 0 0 1 0-1m0 3h2v1h-2a.5.5 0 0 1 0-1m0 3h13a.5.5 0 0 1 0 1h-13a.5.5 0 0 1 0-1m13-2h-2v-1h2a.5.5 0 0 1 0 1m-2-4v1h2a.5.5 0 0 0 0-1zm-.758-3q.312.465.502 1H16.5a.5.5 0 0 0 0-1zM7.5 8.5a2.5 2.5 0 0 1 5 0v5a.5.5 0 0 0 1 0v-5a3.5 3.5 0 1 0-7 0v5a.5.5 0 0 0 1 0z");
}

</style>
