<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ci9-hrshr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:toggle-left-48-filled" /></template>
<style>
.ci9-hrshr {
  fill: currentColor;
  d: path("M4 24c0-5.523 4.477-10 10-10h20c5.523 0 10 4.477 10 10s-4.477 10-10 10H14C8.477 34 4 29.523 4 24m5.5 0a5 5 0 1 0 10 0a5 5 0 0 0-10 0");
}

</style>
