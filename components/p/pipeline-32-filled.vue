<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="r1i9n4f4l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:pipeline-32-filled" /></template>
<style>
.r1i9n4f4l {
  fill: currentColor;
  d: path("M2 8a2 2 0 1 1 4 0v16a2 2 0 1 1-4 0zm24 0a2 2 0 1 1 4 0v16a2 2 0 1 1-4 0zm-2 1H8v14h16z");
}

</style>
