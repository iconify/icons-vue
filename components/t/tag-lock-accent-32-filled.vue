<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="tg0kp4w-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:tag-lock-accent-32-filled" /></template>
<style>
.tg0kp4w-b {
  fill: currentColor;
  d: path("M18.684 4a3 3 0 0 0-2.05.81L4.455 16.203a3.25 3.25 0 0 0-.078 4.672l6.326 6.326a3.25 3.25 0 0 0 4.298.264V22a4 4 0 0 1 3.08-3.894a5.002 5.002 0 0 1 8.697-2.383l.344-.344A3 3 0 0 0 28 13.257V6.5A2.5 2.5 0 0 0 25.5 4z");
}

</style>
