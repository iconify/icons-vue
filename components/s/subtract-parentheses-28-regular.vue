<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="k4l5n8a2v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:subtract-parentheses-28-regular" /></template>
<style>
.k4l5n8a2v {
  fill: currentColor;
  d: path("M7.7 5.6a.75.75 0 1 0-.902-1.2A11.98 11.98 0 0 0 2 14c0 3.926 1.886 7.412 4.798 9.6a.75.75 0 1 0 .901-1.2A10.48 10.48 0 0 1 3.5 14c0-3.434 1.648-6.483 4.2-8.4m13.502-1.2a.75.75 0 1 0-.901 1.2A10.48 10.48 0 0 1 24.5 14a10.48 10.48 0 0 1-3.967 8.22a.75.75 0 1 0 .934 1.174A11.98 11.98 0 0 0 26 14c0-3.926-1.886-7.412-4.798-9.6M8.75 13.25a.75.75 0 0 0 0 1.5h10.5a.75.75 0 0 0 0-1.5z");
}

</style>
