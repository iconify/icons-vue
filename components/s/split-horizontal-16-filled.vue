<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="k6hiv-e7u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:split-horizontal-16-filled" /></template>
<style>
.k6hiv-e7u {
  fill: currentColor;
  d: path("M14.5 8a.5.5 0 0 0 0-1h-13a.5.5 0 0 0 0 1zM11 1a2 2 0 0 1 2 2v3H3V3a2 2 0 0 1 2-2zM3 9v3a2 2 0 0 0 2 2h6a2 2 0 0 0 2-2V9z");
}

</style>
