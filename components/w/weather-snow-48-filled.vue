<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o5ih-pbzh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:weather-snow-48-filled" /></template>
<style>
.o5ih-pbzh {
  fill: currentColor;
  d: path("M19.502 36a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m9 0a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m-13.5-2a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m9 0a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m9 0a1.5 1.5 0 1 1 0 3a1.5 1.5 0 0 1 0-3m-9-26c6.338 0 9.933 4.195 10.456 9.26h.16c4.078 0 7.384 3.298 7.384 7.365s-3.306 7.365-7.385 7.365H13.389c-4.078 0-7.384-3.297-7.384-7.365s3.306-7.365 7.384-7.365h.16C14.074 12.161 17.666 8 24.003 8");
}

</style>
