<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uvtl8hbrj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:scan-dash-32-regular" /></template>
<style>
.uvtl8hbrj {
  fill: currentColor;
  d: path("M6.5 4A2.5 2.5 0 0 0 4 6.5V10a1 1 0 1 1-2 0V6.5A4.5 4.5 0 0 1 6.5 2H10a1 1 0 1 1 0 2zm0 24A2.5 2.5 0 0 1 4 25.5V22a1 1 0 1 0-2 0v3.5A4.5 4.5 0 0 0 6.5 30H10a1 1 0 1 0 0-2zM28 6.5A2.5 2.5 0 0 0 25.5 4H22a1 1 0 1 1 0-2h3.5A4.5 4.5 0 0 1 30 6.5V10a1 1 0 1 1-2 0zM25.5 28a2.5 2.5 0 0 0 2.5-2.5V22a1 1 0 1 1 2 0v3.5a4.5 4.5 0 0 1-4.5 4.5H22a1 1 0 1 1 0-2zM8 16a1 1 0 0 1 1-1h14a1 1 0 1 1 0 2H9a1 1 0 0 1-1-1");
}

</style>
