<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="h57b8lb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-align-justify-rotate-90-20-filled" /></template>
<style>
.h57b8lb2b {
  fill: currentColor;
  d: path("M15.75 2a.75.75 0 0 1 .75.75v14.5a.75.75 0 0 1-1.5 0V2.75a.75.75 0 0 1 .75-.75m-5 0a.75.75 0 0 1 .75.75v14.5a.75.75 0 0 1-1.5 0V2.75a.75.75 0 0 1 .75-.75m-4.25.75a.75.75 0 0 0-1.5 0v14.5a.75.75 0 0 0 1.5 0z");
}

</style>
