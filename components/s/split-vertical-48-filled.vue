<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="m66r9p21x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:split-vertical-48-filled" /></template>
<style>
.m66r9p21x {
  fill: currentColor;
  d: path("M25.5 5.25a1.25 1.25 0 1 0-2.5 0v37.5a1.25 1.25 0 1 0 2.5 0zM39.75 40H27.5V8h12.25A4.25 4.25 0 0 1 44 12.25v23.5A4.25 4.25 0 0 1 39.75 40M21 8H8.25A4.25 4.25 0 0 0 4 12.25v23.5A4.25 4.25 0 0 0 8.25 40H21z");
}

</style>
