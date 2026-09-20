<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vvd1uachd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mobile-optimized-48-filled" /></template>
<style>
.vvd1uachd {
  fill: currentColor;
  d: path("M10.75 4c.69 0 1.25.56 1.25 1.25v5.5c0 .69-.56 1.25-1.25 1.25h-5.5a1.25 1.25 0 1 1 0-2.5H9.5V5.25c0-.69.56-1.25 1.25-1.25m26.5 0c.69 0 1.25.56 1.25 1.25V9.5h4.25a1.25 1.25 0 1 1 0 2.5h-5.5c-.69 0-1.25-.56-1.25-1.25v-5.5c0-.69.56-1.25 1.25-1.25M14 14.5a2.5 2.5 0 0 1 2.5-2.5h15a2.5 2.5 0 0 1 2.5 2.5v19a2.5 2.5 0 0 1-2.5 2.5h-15a2.5 2.5 0 0 1-2.5-2.5zm6.25 4.5a1.25 1.25 0 1 0 0 2.5h7.5a1.25 1.25 0 1 0 0-2.5zm0 5a1.25 1.25 0 1 0 0 2.5h4.5a1.25 1.25 0 1 0 0-2.5zM12 42.75a1.25 1.25 0 1 1-2.5 0V38.5H5.25a1.25 1.25 0 1 1 0-2.5h5.5c.69 0 1.25.56 1.25 1.25zm26.5 0a1.25 1.25 0 1 1-2.5 0v-5.5c0-.69.56-1.25 1.25-1.25h5.5a1.25 1.25 0 1 1 0 2.5H38.5z");
}

</style>
