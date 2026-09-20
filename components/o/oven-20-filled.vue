<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="zd-m25bdw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:oven-20-filled" /></template>
<style>
.zd-m25bdw {
  fill: currentColor;
  d: path("M6 3a3 3 0 0 0-3 3v1h14V6a3 3 0 0 0-3-3zm1.5 2.5a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m6.5 0a.75.75 0 1 1-1.5 0a.75.75 0 0 1 1.5 0m-4 .75a.75.75 0 1 1 0-1.5a.75.75 0 0 1 0 1.5M3 14V8h14v6a3 3 0 0 1-3 3H6a3 3 0 0 1-3-3m3.5-4a.5.5 0 0 0-.5.5v3a.5.5 0 0 0 .5.5h7a.5.5 0 0 0 .5-.5v-3a.5.5 0 0 0-.5-.5z");
}

</style>
