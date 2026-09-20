<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="sorp06bgf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:steps-16-filled" /></template>
<style>
.sorp06bgf {
  fill: currentColor;
  d: path("M5 13H2c-.552 0-1-.449-1-1V9c0-.551.448-1 1-1h3V6c0-.551.448-1 1-1h3V2c0-.551.448-1 1-1h3c.552 0 1 .449 1 1v4h-1V2h-3v3c0 .551-.448 1-1 1H6v2c0 .551-.448 1-1 1H2v3h3zm10-.5V8c0-.551-.448-1-1-1h-3c-.552 0-1 .449-1 1v2H7c-.552 0-1 .449-1 1v3c0 .551.448 1 1 1h5.5c1.379 0 2.5-1.122 2.5-2.5");
}

</style>
