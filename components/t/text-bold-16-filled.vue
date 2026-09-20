<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="bvm5gc5-b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:text-bold-16-filled" /></template>
<style>
.bvm5gc5-b {
  fill: currentColor;
  d: path("M4 3.3C4 2.6 4.6 2 5.3 2h3.3c2 0 3.5 1.7 3.5 3.5c0 .7-.2 1.4-.6 1.9c.7.6 1.2 1.6 1.2 2.8c0 2.4-2 3.7-3.7 3.7H5.3c-.7.1-1.3-.5-1.3-1.2zm2.6 1.3v1.9h2c.5 0 1-.4 1-1c0-.5-.4-1-1-1h-2zm0 4.5v2.4H9c.6 0 1.2-.5 1.2-1.2S9.6 9.1 9 9.1z");
}

</style>
