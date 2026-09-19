<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sq4l5ybuc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:sharp-panorama-vertical-select" /></template>
<style>
.sq4l5ybuc {
  fill: currentColor;
  d: path("M18.49 11.99c0-5.25 1.54-9.01 1.92-10H3.59c.76 2.16 1.9 5.21 1.9 10c0 4.78-1.17 7.91-1.9 10H20.4c-.74-2.08-1.91-5.23-1.91-10");
}

</style>
