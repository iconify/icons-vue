<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="fx_4oyb5q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:square-hint-20-filled" /></template>
<style>
.fx_4oyb5q {
  fill: currentColor;
  d: path("M9.25 3a.75.75 0 0 0 0 1.5h1.5a.75.75 0 0 0 0-1.5zM3 10.75a.75.75 0 0 0 1.5 0v-1.5a.75.75 0 0 0-1.5 0zm5.5 5.5a.75.75 0 0 1 .75-.75h1.5a.75.75 0 0 1 0 1.5h-1.5a.75.75 0 0 1-.75-.75m7-5.5a.75.75 0 0 0 1.5 0v-1.5a.75.75 0 0 0-1.5 0zm-9.5-7A.75.75 0 0 0 5.25 3A2.25 2.25 0 0 0 3 5.25a.75.75 0 0 0 1.5 0a.75.75 0 0 1 .75-.75a.75.75 0 0 0 .75-.75M5.25 17a.75.75 0 0 0 0-1.5a.75.75 0 0 1-.75-.75a.75.75 0 0 0-1.5 0A2.25 2.25 0 0 0 5.25 17M14 3.75a.75.75 0 0 1 .75-.75A2.25 2.25 0 0 1 17 5.25a.75.75 0 0 1-1.5 0a.75.75 0 0 0-.75-.75a.75.75 0 0 1-.75-.75M14.75 17a.75.75 0 0 1 0-1.5a.75.75 0 0 0 .75-.75a.75.75 0 0 1 1.5 0A2.25 2.25 0 0 1 14.75 17");
}

</style>
