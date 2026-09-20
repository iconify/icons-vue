<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tngez_h6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:table-picnic-16-filled" /></template>
<style>
.tngez_h6g {
  fill: currentColor;
  d: path("M3.446 13.032a.751.751 0 0 1-1.39-.564l.798-1.968h1.619zm10.5-.564a.751.751 0 0 1-1.39.564L11.529 10.5h1.62zM5.487 8h5.028L9.299 5h1.62l1.216 3h2.115a.75.75 0 0 1 0 1.5H1.75a.75.75 0 0 1 0-1.5h2.117l1.216-3h1.62zm6.763-5.5a.75.75 0 0 1 0 1.5h-8.5a.75.75 0 0 1 0-1.5z");
}

</style>
