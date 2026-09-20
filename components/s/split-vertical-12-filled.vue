<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="rmsyu2v2j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:split-vertical-12-filled" /></template>
<style>
.rmsyu2v2j {
  fill: currentColor;
  d: path("M6 1.5a.5.5 0 0 0-1 0v9a.5.5 0 0 0 1 0zm-5 2A1.5 1.5 0 0 1 2.5 2H4v8H2.5A1.5 1.5 0 0 1 1 8.5zM7 10h1.5A1.5 1.5 0 0 0 10 8.5v-5A1.5 1.5 0 0 0 8.5 2H7z");
}

</style>
