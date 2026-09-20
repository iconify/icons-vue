<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="li6erhbyu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:seat-multiple-stadium-16-regular" /></template>
<style>
.li6erhbyu {
  fill: currentColor;
  d: path("M10.25 2A2.75 2.75 0 0 1 13 4.75v1.3a2.5 2.5 0 0 1 2 2.45V12a2 2 0 0 1-2 2h-1a2 2 0 0 1-1.5-.68c-.367.416-.902.68-1.5.68H7a2 2 0 0 1-1.5-.68c-.367.416-.902.68-1.5.68H3a2 2 0 0 1-2-2V8.5a2.5 2.5 0 0 1 2-2.45v-1.3a2.75 2.75 0 0 1 5-1.578A2.75 2.75 0 0 1 10.25 2M3 11a1 1 0 1 0 0 2h1a1 1 0 1 0 0-2zm4 0a1 1 0 1 0 0 2h2a1 1 0 1 0 0-2zm5 0a1 1 0 1 0 0 2h1a1 1 0 1 0 0-2zM3.5 7A1.5 1.5 0 0 0 2 8.5v1.77A2 2 0 0 1 3 10h1c.365 0 .706.1 1 .27V8.5A1.5 1.5 0 0 0 3.5 7M8 7a2 2 0 0 0-2 2v1.27A2 2 0 0 1 7 10h2c.365 0 .706.1 1 .27V9a2 2 0 0 0-2-2m4.5 0A1.5 1.5 0 0 0 11 8.5v1.77a2 2 0 0 1 1-.27h1c.365 0 .706.1 1 .27V8.5A1.5 1.5 0 0 0 12.5 7M5.75 3A1.75 1.75 0 0 0 4 4.75v1.3a2.5 2.5 0 0 1 1.62 1.129A3 3 0 0 1 7.5 6.04V4.75A1.75 1.75 0 0 0 5.75 3m4.5 0A1.75 1.75 0 0 0 8.5 4.75v1.291a3 3 0 0 1 1.88 1.138A2.5 2.5 0 0 1 12 6.049V4.75A1.75 1.75 0 0 0 10.25 3");
}

</style>
