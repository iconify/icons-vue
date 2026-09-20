<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="uw9jvubql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-bullet-list-edit-20-regular" /></template>
<style>
.uw9jvubql {
  fill: currentColor;
  d: path("M16.81 10.548a1.87 1.87 0 1 1 2.644 2.644l-4.829 4.83a2.2 2.2 0 0 1-1.021.578l-1.498.375a.89.89 0 0 1-1.079-1.08l.374-1.497c.097-.387.297-.74.579-1.021zM3 13.5a1 1 0 1 1 0 2a1 1 0 0 1 0-2m8.273 1.17q-.156.156-.288.33H6.5a.5.5 0 0 1 0-1h5.442zM3 8.5a1 1 0 1 1 0 2a1 1 0 0 1 0-2m14.5.5q.1 0 .189.037c-.581.09-1.14.357-1.587.804l-.159.159H6.5a.5.5 0 0 1 0-1zM3 3.5a1 1 0 1 1 0 2a1 1 0 0 1 0-2m14.5.5a.5.5 0 0 1 0 1h-11a.5.5 0 0 1 0-1z");
}

</style>
