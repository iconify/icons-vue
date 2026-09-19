<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a-qgjebdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-file-download-done" /></template>
<style>
.a-qgjebdn {
  fill: currentColor;
  d: path("M20.13 5.41L18.72 4l-9.19 9.19l-4.25-4.24l-1.41 1.41l5.66 5.66zM5 18h14v2H5z");
}

</style>
