<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="xqzsl3boq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:prohibited-12-filled" /></template>
<style>
.xqzsl3boq {
  fill: currentColor;
  d: path("M11 6A5 5 0 1 1 1 6a5 5 0 0 1 10 0M9.5 6c0-.695-.203-1.342-.552-1.887L4.113 8.948A3.5 3.5 0 0 0 9.5 6M7.888 3.052a3.5 3.5 0 0 0-4.836 4.836z");
}

</style>
