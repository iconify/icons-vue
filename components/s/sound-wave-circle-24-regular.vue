<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ms-3yr14h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:sound-wave-circle-24-regular" /></template>
<style>
.ms-3yr14h {
  fill: currentColor;
  d: path("M11 8.75a.75.75 0 0 0-1.5 0v6.5a.75.75 0 0 0 1.5 0zm6 0a.75.75 0 0 0-1.5 0v6.5a.75.75 0 0 0 1.5 0zm-3 1.5a.75.75 0 0 0-1.5 0v3.5a.75.75 0 0 0 1.5 0zm-6 .5a.75.75 0 0 0-1.5 0v2.5a.75.75 0 0 0 1.5 0zM12 2C6.477 2 2 6.477 2 12s4.477 10 10 10s10-4.477 10-10S17.523 2 12 2M3.5 12a8.5 8.5 0 1 1 17 0a8.5 8.5 0 0 1-17 0");
}

</style>
