<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="bh74qmwfc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-bullet-list-edit-20-filled" /></template>
<style>
.bh74qmwfc {
  fill: currentColor;
  d: path("M16.81 10.548a1.87 1.87 0 1 1 2.644 2.644l-4.829 4.83a2.2 2.2 0 0 1-1.021.578l-1.498.375a.89.89 0 0 1-1.079-1.08l.374-1.497c.097-.387.297-.74.579-1.021zM3.25 13.5a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5m8.023 1.17a3.2 3.2 0 0 0-.597.83H7.75a.75.75 0 0 1 0-1.5h4.192zM3.25 8.5a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5m14 .5q.159 0 .297.06c-.53.11-1.034.37-1.445.78l-.659.66H7.75a.75.75 0 0 1 0-1.5zm-14-5.5a1.25 1.25 0 1 1 0 2.5a1.25 1.25 0 0 1 0-2.5m14 .5a.75.75 0 0 1 0 1.5h-9.5a.75.75 0 0 1 0-1.5z");
}

</style>
