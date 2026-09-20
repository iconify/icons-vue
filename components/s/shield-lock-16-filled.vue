<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="e2s1dzq7g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:shield-lock-16-filled" /></template>
<style>
.e2s1dzq7g {
  fill: currentColor;
  d: path("M8.355 2.147a.5.5 0 0 0-.708 0C6.404 3.388 5.03 4 3.5 4a.5.5 0 0 0-.5.5v3.001c0 2.923 1.354 4.996 4 6.151V10a2 2 0 0 1 1.5-1.937V8A3 3 0 0 1 13 5.401V4.5a.5.5 0 0 0-.5-.5c-1.531 0-2.905-.61-4.145-1.853M9.5 9V8a2 2 0 1 1 4 0v1h.5a1 1 0 0 1 1 1v4a1 1 0 0 1-1 1H9a1 1 0 0 1-1-1v-4a1 1 0 0 1 1-1zm1-1v1h2V8a1 1 0 1 0-2 0m1.75 4a.75.75 0 1 0-1.5 0a.75.75 0 0 0 1.5 0");
}

</style>
