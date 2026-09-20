<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="kkhzrliiz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:quiz-28-filled" /></template>
<style>
.kkhzrliiz {
  fill: currentColor;
  d: path("M21.25 3A3.75 3.75 0 0 1 25 6.75v14.5A3.75 3.75 0 0 1 21.25 25H6.75A3.75 3.75 0 0 1 3 21.25V6.75A3.75 3.75 0 0 1 6.75 3zM6.75 20.001a.75.75 0 0 0 0 1.5h14.5a.75.75 0 0 0 0-1.5zm0-4.003a.75.75 0 0 0 0 1.5h14.5a.75.75 0 1 0 0-1.5zM11.502 6a.75.75 0 0 0-.692.457L8.06 12.96a.75.75 0 0 0 1.38.585l.442-1.043h3.236l.442 1.043a.75.75 0 0 0 1.38-.584l-2.748-6.503a.75.75 0 0 0-.69-.458m6.248 0a.75.75 0 0 0-.75.75V8h-1.248a.75.75 0 0 0 0 1.5H17v1.248a.75.75 0 0 0 1.5 0V9.5h1.25a.75.75 0 0 0 0-1.5H18.5V6.75a.75.75 0 0 0-.75-.75m-5.266 5.002h-1.967l.984-2.327z");
}

</style>
