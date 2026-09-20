<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zx8euib-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:video-prohibited-24-filled" /></template>
<style>
.zx8euib-m {
  fill: currentColor;
  d: path("M6.5 11a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m-2.248 8.809a4 4 0 0 0 5.557-5.557zM11.75 5A3.25 3.25 0 0 1 15 8.25v7.5a3.25 3.25 0 0 1-2.46 3.152A6.5 6.5 0 0 0 2 11.812V8.25A3.25 3.25 0 0 1 5.25 5zM6.5 12.5a4 4 0 0 0-3.309 6.248l5.557-5.557A4 4 0 0 0 6.5 12.5m12.758-6.187c1.16-.801 2.744.03 2.744 1.44v8.495c0 1.41-1.583 2.241-2.744 1.44L16 15.44V8.563z");
}

</style>
