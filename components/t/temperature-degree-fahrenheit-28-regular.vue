<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="o8n8m-m7z"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:temperature-degree-fahrenheit-28-regular" /></template>
<style>
.o8n8m-m7z {
  fill: currentColor;
  d: path("M5 8.5a2 2 0 1 1 4 0a2 2 0 0 1-4 0M7 5a3.5 3.5 0 1 0 0 7a3.5 3.5 0 0 0 0-7m6.75 0a.75.75 0 0 0-.75.75v16.5a.75.75 0 0 0 1.5 0V14.5h7.75a.75.75 0 0 0 0-1.5H14.5V6.5h8.75a.75.75 0 0 0 0-1.5z");
}

</style>
